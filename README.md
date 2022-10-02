# PowerShell - Inline C# compilation payload template

At the time of writing, the [Havoc C2 Framwork](https://github.com/HavocFramework/Havoc) is fairly new and still in a pre-release state. 
I was interested in testing [5pider](https://twitter.com/C5pider)'s work - so I prepared a lab & exploited a fully patched Windows 11 client. 
In order to do so, I wanted to use the inline C# compilation capability of PowerShell, as I saw it recently in [John Hammond](https://www.youtube.com/watch?v=EwEwRLedeKI)'s video.

The setup of Havoc and the payload preparation can be read in my [blog post](https://payload.cafe/2022/10/02/havoc-c2-intro-inline-csharp-compilation-within-powershell/). The payload template code can be found [here](https://github.com/TheConciergeDev/PS_with_inline_csharp_compilation/blob/master/execute_inline_csharp_code_within_powershell.ps1). Please don't use it for any malicious intent.

A video of this can be seen on [YouTube](https://www.youtube.com/watch?v=pso2LAONCJ8)


As always, any feedback is appreciated - thanks guys!
