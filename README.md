# WebView2 Runtime Archive

[中文文档](README.zh.md)

WebView2 `Fixed Version Runtime` and `NuGet Package` archive

> Official resources
> - [WebView2 Docs](https://docs.microsoft.com/en-us/microsoft-edge/webview2/)
> - [WebView2 Runtime Download](https://developer.microsoft.com/en-us/microsoft-edge/webview2/#download-section)
> - [WebView2 NuGet Package](https://www.nuget.org/packages/Microsoft.Web.WebView2#versions-body-tab)
> - [WebView2 Feedback](https://github.com/MicrosoftEdge/WebView2Feedback/issues)

## Why did I create this repository?

Around early 2021, I started following and started using Microsoft's WebView2. Before this, I have been using CefSharp to develop hybrid applications, both are very easy to use, each has its own advantages and disadvantages, I think WebView2 will have more development potential!

In actual development, I prefer to use Fixed Version Runtime, because it is easier to publish software to run on other computers.

After a period of time, I found that on the WebView2 Runtime download page, Fixed Version only provides the latest two versions for download. Therefore, I plan to pay more attention to the updates of WebView2 in the future, and regularly download Fixed Version Runtime and archive it, to use any version in future projects.

![./screenshot/en-us.png](./screenshot/en-us.png)

After another long time, I found in [WebView2Feedback/issues/2673](https://github.com/MicrosoftEdge/WebView2Feedback/issues/2673) and [WebView2Feedback/discussions/2007](https://github.com/MicrosoftEdge/WebView2Feedback/discussions/2007) someone mentioned this problem, so I created this repository and uploaded my archived files through `Github Releases` (at the same time, I also uploaded the NuGet package of the corresponding version) for everyone to download and use.

## Archive

> The `90` version lacks the arm64 arch archive (because the official website download link was wrong at that time)  
> The `93 ~ 94` versions are not archived (maybe busy with other things during that time, so I forgot to download)

[All Releases](https://github.com/westinyang/WebView2RuntimeArchive/releases)

## Expand

I'm not good at making NuGet packages that contain a fixed version of the WebView2 runtime, but you can refer to this project: [ProKn1fe/WebView2.Runtime](https://github.com/ProKn1fe/WebView2.Runtime)

## Change

### 2024-12-03

I found that the official website seems to no longer provide downloads of fixed version runtimes. If this is true, then this project will no longer be updated...

![./screenshot/zh-cn.png](./screenshot/20241203_en-us.png)

## Sponsoring

> The "memory" of the Internet may be limited, but our love is unlimited!

If you find this project useful you can [buymeacoffee](https://www.buymeacoffee.com/westinyang).

Alternatively, just hit the 'star' here on github.
