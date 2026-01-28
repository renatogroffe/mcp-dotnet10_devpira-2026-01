# mcp-dotnet10_devpira-2026-01
Conteúdos sobre MCPs de apresentação realizada no dia 10/01/2026, durante a edição local do .NET Conf em Piracicaba. Tecnologias abordadas: MCP, GitHub Copilot, Docker, .NET 10, ASP.NET Core, NuGet, Visual Studio Code, Grafana stack, Microsoft Foundry, k6...

---

## Exemplos da palestra
- [MCP Server de geração de dados fake criado com .NET 10 (pacote NuGet)](https://github.com/renatogroffe/dotnet10-nuget-mcp-fakedata)
- [MCP Server de geração de dados fake criado com .NET 10 (container)](https://github.com/renatogroffe/dotnet10-consoleapp-mcp-fakedata)
- [MCP Server de contagem de acessos com monitoramento via stack Grafana + OpenTelemetry](https://github.com/renatogroffe/aspnetcore10-mcp-otel-grafana-redis_contagem)
- [MCP Server de contagem de acessos com monitoramento via Azure Application Insights + OpenTelemetry](https://github.com/renatogroffe/aspnetcore10-mcp-otel-appinsights-redis_contagem)
- [FakeDataMcpServer - MCP Server disponibilizado como um pacote NuGet (pacote NuGet)](https://www.nuget.org/packages/FakeDataMcpServer/1.0.0)
- [k6 + Azure DevOps: exemplo de teste automatizado de um MCP Server](https://github.com/renatogroffe/k6-mcps-tests-azdevops-pipelines)
- [Exemplo de uso da ferramenta MCP Audit (APIsec) em um pipeline do Azure DevOps](https://github.com/renatogroffe/azdevops-apisec-mcp-audit_v1.0.0)

## Referências

- [Create a minimal MCP server using C# and publish to NuGet | Microsoft Learn](https://learn.microsoft.com/en-us/dotnet/ai/quickstarts/build-mcp-server)
- [Extensão do k6 para teste de MCP Servers](https://github.com/grafana/xk6-mcp)
- [OWASP MCP Top 10 | OWASP Foundation](https://owasp.org/www-project-mcp-top-10/)
- [APIsec MCP Discovery and Audit](https://apisec-inc.github.io/mcp-audit/)
