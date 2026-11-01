# Third-party notices

This distribution includes the Microsoft .NET runtime and Windows Desktop runtime. Their license and third-party notices are provided in LICENSE.txt and ThirdPartyNotices.txt in the portable distribution. Source: https://github.com/dotnet/runtime and https://github.com/dotnet/wpf .

The application uses Windows Shell COM interfaces supplied by Windows. Interface contracts were checked against the local Windows SDK 10.0.26100.0 and Microsoft Learn documentation.

ExplorerTabUtility (https://github.com/w4po/ExplorerTabUtility) was consulted for window monitoring, tab reuse and source-window transfer behavior. Its MIT license applies to that upstream project. This project does not bundle the upstream application or its binary dependencies; the Shell adapter and workspace UI are implemented locally. The research manifest records the upstream revision consulted.

REA (https://github.com/morluto/rea) was consulted for its evidence-oriented analysis workflow. REA is not a runtime dependency and was not registered as an MCP server for this project.

Clover installer modules were inspected offline as user-supplied reference material. No Clover code, resources, icons or binaries are included in the portable package or source archive. Static import evidence does not establish full behavior or algorithm equivalence.

Development-only tools such as the .NET SDK, pefile and py7zr are not included in the user distribution.
