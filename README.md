<div align="center">

  <a href="https://siliconfps.github.io/" title="Visitar o portal SILICONFPS">
    <img src="https://siliconfps.github.io/avatarupscaled-v2.png" alt="Avatar SILICONFPS" width="168" />
  </a>

  <h1>SILICONFPS</h1>

  <p>
    <strong>IA agêntica · software de sistemas · ferramentas de terminal · baixa latência</strong>
  </p>

  <p>
    Software open source para quem prefere <strong>velocidade, controle e eficiência</strong>.
  </p>

  <p>
    <a href="https://siliconfps.github.io/"><img src="https://img.shields.io/badge/PORTAL-00ff88?style=for-the-badge&logo=googlechrome&logoColor=07110d" alt="Portal oficial" /></a>
    <a href="https://github.com/siliconfps?tab=repositories"><img src="https://img.shields.io/badge/PROJETOS-161b22?style=for-the-badge&logo=github&logoColor=white" alt="Projetos no GitHub" /></a>
    <a href="https://youtube.com/@siliconfps"><img src="https://img.shields.io/badge/YOUTUBE-ff0033?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" /></a>
  </p>

  <p>
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=17&duration=2800&pause=900&color=00FF88&center=true&vCenter=true&width=720&lines=Agentes+aut%C3%B4nomos+para+desenvolvimento;Ferramentas+standalone+para+Windows;Monitoramento+de+hardware+em+tempo+real;Performance+e+automa%C3%A7%C3%A3o+de+sistemas" alt="Áreas de atuação da SILICONFPS" />
  </p>

  <sub>
    <a href="#projetos-em-destaque">Destaques</a> ·
    <a href="#ecossistema">Ecossistema</a> ·
    <a href="#tecnologias">Tecnologias</a> ·
    <a href="#contato">Contato</a>
  </sub>

</div>

---

## Sobre

Desenvolvo soluções nas interseções entre **Inteligência Artificial**, **engenharia de performance** e **software de sistemas**. O objetivo é direto: transformar tarefas complexas em ferramentas rápidas, transparentes e fáceis de operar.

- **IA & automação:** agentes CLI/TUI, subagentes, memória persistente, worktrees e integrações via Model Context Protocol.
- **Terminal & produtividade:** aplicações standalone, offline e com integração nativa ao Windows.
- **Performance:** automações de pós-instalação, redução de overhead e ajustes de baixa latência.
- **Hardware:** telemetria leve de CPU/GPU para Windows e ambientes Linux.
- **Open source:** manutenção e modernização de utilitários para a comunidade.

---

## Projetos em destaque

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🌸 SiliconFlower</h3>
      <p align="center">
        <a href="https://github.com/siliconfps/siliconflower"><img src="https://img.shields.io/badge/v0.2.4-00ff88?style=flat-square&label=release&labelColor=161b22" alt="SiliconFlower v0.2.4" /></a>
        <img src="https://img.shields.io/badge/Windows-0078D4?style=flat-square&logo=windows&logoColor=white" alt="Windows" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
        <img src="https://img.shields.io/badge/MCP-8A2BE2?style=flat-square" alt="MCP" />
      </p>
      <p>
        Harness de agentes de IA de alta performance para desenvolvimento no Windows. Reúne <strong>34 ferramentas nativas</strong>, subagentes concorrentes, tarefas em background, memória persistente, Git worktrees, RepoMap, busca web, hooks e MCP.
      </p>
      <p>
        Compatível com <strong>OpenAI, Anthropic, OpenRouter, SiliconFlow</strong> e APIs equivalentes. Pode ser compilado como um único executável <code>.exe</code> via Bun.
      </p>
      <p align="center">
        <strong><a href="https://github.com/siliconfps/siliconflower">Código e documentação</a></strong> ·
        <strong><a href="https://siliconfps.github.io/siliconflower.html#/1">Demonstração</a></strong>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">📑 MarkiiDown</h3>
      <p align="center">
        <a href="https://github.com/siliconfps/markiidown"><img src="https://img.shields.io/badge/v1.1.0-00ff88?style=flat-square&label=release&labelColor=161b22" alt="MarkiiDown v1.1.0" /></a>
        <img src="https://img.shields.io/badge/Windows_x64-0078D4?style=flat-square&logo=windows&logoColor=white" alt="Windows x64" />
        <img src="https://img.shields.io/badge/Offline-161b22?style=flat-square&logo=shield&logoColor=00ff88" alt="Offline" />
        <img src="https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white" alt="Bun" />
      </p>
      <p>
        Leitor de Markdown <strong>standalone e 100% offline</strong>, com pager TUI, busca, sumário navegável, quebra responsiva de linhas, realce de código, modo watch e exportação HTML autocontida.
      </p>
      <p>
        Instala no espaço do usuário, sem privilégios de administrador, e adiciona integração ao menu de contexto do Windows Explorer. O executável portátil não exige Bun ou Node.js.
      </p>
      <p align="center">
        <strong><a href="https://github.com/siliconfps/markiidown">Código e documentação</a></strong>
      </p>
    </td>
  </tr>
</table>

---

## Ecossistema

| Área | Projeto | O que entrega | Stack principal |
| :--- | :--- | :--- | :--- |
| ⚡ Performance | [Otimizador Windows](https://github.com/siliconfps/otimizador-windows) | Automação de pós-instalação com 19 ajustes de desempenho e privacidade para Windows 10/11. | PowerShell |
| 📊 Monitoramento | [GPU/CPU Monitor Windows](https://github.com/siliconfps/gpu-cpu-monitor-windows) | Telemetria de CPU/GPU em tempo real, bandeja do sistema e build single-file em .NET 9. | C# / .NET |
| 🧹 Manutenção | [Little Registry Cleaner](https://github.com/siliconfps/LittleRegistryCleaner) | Limpeza do Registro, backups, restauração e gerenciamento de inicialização/desinstalação. | C# / .NET |
| 🛡️ Diagnóstico | [Check CPU Mitigations](https://github.com/siliconfps/check-cpu-mitigations) | Auditoria das mitigações de Spectre, Meltdown, MDS e outras vulnerabilidades de CPU. | PowerShell |
| 🦀 Terminal | [Editor Seco-Seco](https://github.com/siliconfps/editor-seco-seco) | Editor CLI minimalista com inicialização rápida e baixo consumo de memória. | Rust |
| 📀 Linux | [WoeUSB Remastered](https://github.com/siliconfps/WoeUSB-remast) | Manutenção da ferramenta para criar mídia inicializável do Windows a partir do Linux. | Python / Shell |
| 🐧 Hardware Linux | [Hardview](https://github.com/siliconfps/hardview) · [cpufreq-perf](https://github.com/siliconfps/ubuntu-cpufreq-perf) · [AMD Overclock](https://github.com/siliconfps/overclock-amd) | Informações do sistema, perfis de frequência e controle de power cap. | Shell |
| 🖥️ Desktop Linux | [GNOME CPU](https://github.com/siliconfps/gnome-cpu-monitor) · [GNOME GPU](https://github.com/siliconfps/gnome-gpu-monitor) · [XFCE CPU](https://github.com/siliconfps/xfce4-cpu-plugin) · [XFCE GPU](https://github.com/siliconfps/xfce4-gpu-plugin) · [LXPanel](https://github.com/siliconfps/lxpanel-cpu-gpu-monitor) | Plugins e extensões leves para monitoramento no painel. | C / JavaScript / Shell |

<div align="center">
  <a href="https://github.com/siliconfps?tab=repositories">
    <img src="https://img.shields.io/badge/Explorar_todos_os_reposit%C3%B3rios-161b22?style=for-the-badge&logo=github&logoColor=white" alt="Explorar todos os repositórios" />
  </a>
</div>

---

## Tecnologias

<div align="center">

  <p><strong>IA & orquestração</strong></p>
  <p>
    <img src="https://img.shields.io/badge/Agentic_AI-00ff88?style=flat-square&logo=openai&logoColor=07110d" alt="Agentic AI" />
    <img src="https://img.shields.io/badge/Model_Context_Protocol-8A2BE2?style=flat-square" alt="Model Context Protocol" />
    <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI" />
    <img src="https://img.shields.io/badge/Anthropic-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Anthropic" />
  </p>

  <p><strong>Linguagens & runtimes</strong></p>
  <p>
    <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
    <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
    <img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="C#" />
    <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=111111" alt="C" />
    <img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" alt="PowerShell" />
    <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white" alt="Bun" />
    <img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET" />
  </p>

  <p><strong>Plataformas</strong></p>
  <p>
    <img src="https://img.shields.io/badge/Windows_10_%2F_11-0078D4?style=flat-square&logo=windows&logoColor=white" alt="Windows 10 e 11" />
    <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=111111" alt="Linux" />
    <img src="https://img.shields.io/badge/GNOME-4A86CF?style=flat-square&logo=gnome&logoColor=white" alt="GNOME" />
    <img src="https://img.shields.io/badge/XFCE-2284F2?style=flat-square&logo=xfce&logoColor=white" alt="XFCE" />
  </p>

</div>

---

## Atividade no GitHub

<div align="center">
  <a href="https://github.com/siliconfps">
    <img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=siliconfps&theme=github_dark" alt="Estatísticas do GitHub" />
  </a>
  <a href="https://github.com/siliconfps?tab=repositories">
    <img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=siliconfps&theme=github_dark" alt="Linguagens mais usadas por repositório" />
  </a>
</div>

---

## Contato

<div align="center">
  <p>
    <a href="https://siliconfps.github.io/"><img src="https://img.shields.io/badge/siliconfps.github.io-00ff88?style=for-the-badge&logo=googlechrome&logoColor=07110d" alt="Portal oficial" /></a>
    <a href="https://youtube.com/@siliconfps"><img src="https://img.shields.io/badge/@siliconfps-ff0033?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" /></a>
    <a href="mailto:redesassessoria@gmail.com"><img src="https://img.shields.io/badge/Enviar_e--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail" /></a>
  </p>

  <sub>Brasil 🇧🇷 · Projetado com foco em alta performance, autonomia e eficiência.</sub>
</div>
