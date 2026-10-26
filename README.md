# Doca

**Um dock para cada momento do seu Windows.** Dock para Windows 10 e 11 com a lente de ampliação do Mac, mais de 25 widgets e ambientes (Trabalho, Estudo, Lazer), cada um com seus apps, widgets e janelas.

[![Baixar na Microsoft Store](https://get.microsoft.com/images/pt-br%20dark.svg)](https://apps.microsoft.com/detail/9NHPM85B060H?referrer=appbadge&mode=direct)

[![Doca](https://doca.racoelho.com.br/assets/og.png)](https://doca.racoelho.com.br)

Site: **[doca.racoelho.com.br](https://doca.racoelho.com.br)** · Case técnico: **[racoelho.com.br/projetos](https://racoelho.com.br/projetos)**

## Por dentro

- **C# / .NET 10 + WinUI 3**, publicado com **Native AOT** (x64 e ARM64): inicia rápido e sem runtime para instalar
- Win32 via **CsWin32**: lista de janelas, AppUserModelID, prévias ao vivo (DWM thumbnails), arrastar e soltar do shell
- Lente de ampliação com vidro acrílico, reposicionamento por monitor, escala e área útil
- Um processo vigia que restaura o dock se ele cair
- Núcleo (`Doca.Core`) sem dependência de Windows, coberto por testes; distribuição pela Microsoft Store (MSIX) e por instalador próprio com atualização automática

## Este repositório

O código do Doca é privado. Aqui ficam só os instaladores e o changelog de cada versão, em [Releases](https://github.com/rafa-coelho/doca-releases/releases).

---

**Doca** is a dock for Windows 10/11 with macOS-style magnification, 25+ widgets and environments (Work, Study, Leisure), each with its own apps, widgets and windows. Built in C# with WinUI 3 and Native AOT, available on the [Microsoft Store](https://apps.microsoft.com/detail/9NHPM85B060H). This repository hosts installers and release notes only.
