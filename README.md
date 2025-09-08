# Binding test for ItemTemplate

If the template is embedded straight into `App.xaml` we get an error

    1>App.xaml(14,27): XamlCompiler error WMC0612: The XAML Binary Format (XBF) generator reported syntax error '0x09C4' : Property Not Found

pointing to `x:DataType` even though Intellisense knows about these properties.