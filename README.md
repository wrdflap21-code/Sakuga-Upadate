# Sakugaloader

<p align="center">
  <a href="https://github.com/wrdflap21-code/Sakuga-Upadate/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/wrdflap21-code/Sakuga-Upadate?label=latest&color=ff315b"></a>
  <img alt="Windows" src="https://img.shields.io/badge/Windows-10%20%7C%2011-1d2250">
  <img alt="After Effects 2020+" src="https://img.shields.io/badge/After%20Effects-2020%2B-1d2250">
  <img alt="Free for everyone" src="https://img.shields.io/badge/price-free%20forever-ff315b">
</p>

**Sakugaloader** is a free After Effects panel for animators and editors. Find sakuga (key animation) clips on [Sakugabooru](https://www.sakugabooru.com/), download them, organize them, and drop them into your composition without leaving After Effects.

> It is made to be **free for everyone** and **not for sale**. See [License](#license).

---

## What you can do

- **Search** Sakugabooru by tags, browse recently added and high scored clips, and open pools.
- **Preview** a clip in the panel, then **Download** it, or **Import** it straight into the open composition.
- **Library** with folders, colors and covers. A folder you create is **also created on your PC** (inside your Downloads folder), and clips downloaded to it are saved there, so your files stay organized on disk too.
- **Cut** a clip (trim in and out) before importing.
- **Upscale** clips with Real-ESRGAN anime models, with a **Quick upscale** shortcut in the player.
- **AniVocal** separates vocals and instrumentals from audio.
- **Trace** finds the anime a clip comes from (using trace.moe and AniList).
- **SakugaRemap**, a companion panel to help with time remapping of anime footage.

## Install

You need **Windows 10 or 11**, **After Effects 2020 (17.5) or newer**, and an internet connection. For Upscale, a Vulkan-capable graphics card is recommended.

1. Download the **Sakugaloader Installer** (`Sakugaloader-Installer-v...zip`) from the [installer releases](https://github.com/wrdflap21-code/sakugaloader-tools/releases/latest).
2. **Close After Effects**, extract the ZIP, and run **`Sakugaloader-Setup.exe`**.
3. Press **Install**. The installer downloads the latest Sakugaloader panel from this repository, checks its SHA256, and installs it for your user (no administrator needed).
4. Open After Effects and go to **Window > Extensions > Sakugaloader**.

The **Tools** tab of the installer can also install FFmpeg, Real-ESRGAN (Upscale) and AniVocal for you, and remove them again.

**Good to know**
- The app is **not code-signed yet**, so Windows may show a blue *"Windows protected your PC"* screen. Click **More info**, then **Run anyway**.
- Because the panel is unsigned, the installer turns on Adobe's **CEP developer mode** for the After Effects versions it finds. That is what lets After Effects load it.
- Prefer a manual install? Download `Sakugaloader-v...zip` from [Releases](https://github.com/wrdflap21-code/Sakuga-Upadate/releases/latest), extract it, and run `Sakugaloader-Setup.exe` inside.

## Updates

Updates are automatic. When a new version is published, the panel shows an **update card** with the release notes. Press update, close After Effects when it asks, and a small window installs the new version, with an **automatic backup and rollback** if something goes wrong. Your library, downloads and preferences are kept.

The installer also tells you when a newer **installer** exists and can update itself with one click.

## Safety and privacy

- Every download is verified: panel updates and tools are checked by **SHA256**, and ZIP files are inspected before anything is installed.
- Sakugaloader has **no analytics and no tracking**. It only contacts the services you use: Sakugabooru, GitHub (updates and tool packages), the tool download hosts, and trace.moe / AniList for Trace.
- An optional relay for searches that Sakugabooru blocks exists, but it is **off by default** and explains who receives the search address before you turn it on.

## Found a bug or have an idea?

Open an [issue](https://github.com/wrdflap21-code/Sakuga-Upadate/issues). Please say your After Effects version and what happened. Screenshots help a lot.

## Where things live

| Repository | What is inside |
|---|---|
| **Sakuga-Upadate** (this one) | The Sakugaloader panel releases and the update channel |
| [sakugaloader-tools](https://github.com/wrdflap21-code/sakugaloader-tools) | The installer and the optional tools (AniVocal) |

## License

Sakugaloader uses the **Sakugaloader Free Use License**: free for everyone, and **nobody may sell it or charge for it** (no paid bundles, premium versions, paywalls, ad walls or required donations). You may use it in your own work, including paid client work and monetized videos. The full text is in the `LICENSE` file inside every package.

Sakugaloader is an **unofficial** tool and is not affiliated with Adobe or Sakugabooru. Clips, metadata and images belong to their respective owners: please use them responsibly and do not redistribute or sell downloaded clips as packs. FFmpeg, Real-ESRGAN, AniVocal and its dependencies keep their own licenses.

---

<details>
<summary><b>Em português</b></summary>

**Sakugaloader** é um painel gratuito para o After Effects. Ele ajuda animadores e editores a achar clipes de sakuga (animação-chave) no [Sakugabooru](https://www.sakugabooru.com/), baixar, organizar e levar para a composição sem sair do After Effects.

> Foi feito para ser **gratuito para todos** e **nunca vendido**.

**O que dá para fazer**
- **Buscar** no Sakugabooru por tags, ver clipes recentes e mais bem avaliados, e abrir pools.
- **Prévia** no painel, com **Download** e **Import** direto para a composição.
- **Biblioteca** com pastas, cores e capas. A pasta que você cria também é criada **no seu PC** (dentro da pasta de Downloads), e os clipes baixados para ela ficam lá, organizados no disco.
- **Cortar** um clipe antes de importar.
- **Upscale** com modelos de anime do Real-ESRGAN, com atalho **Quick upscale** no player.
- **AniVocal** separa voz e instrumental.
- **Trace** descobre de qual anime o clipe é (usando trace.moe e AniList).
- **SakugaRemap**, painel auxiliar para remapeamento de tempo em animes.

**Como instalar**
1. Baixe o **Sakugaloader Installer** nas [releases do instalador](https://github.com/wrdflap21-code/sakugaloader-tools/releases/latest).
2. **Feche o After Effects**, extraia o ZIP e abra o **`Sakugaloader-Setup.exe`**.
3. Clique em **Install**. O instalador baixa o painel mais recente, confere o SHA256 e instala para o seu usuário.
4. Abra o After Effects em **Window > Extensions > Sakugaloader**.

Requisitos: Windows 10 ou 11, After Effects 2020 (17.5) ou mais novo e internet. Para o Upscale, é recomendada uma placa de vídeo com suporte a Vulkan.

O programa ainda **não é assinado**, então o Windows pode mostrar o aviso azul: clique em **Mais informações** e depois em **Executar assim mesmo**. Por causa disso, o instalador liga o **modo de desenvolvedor do CEP** da Adobe nas versões do After Effects que encontrar.

**Atualizações** são automáticas: o painel mostra um card com as novidades, e uma janelinha instala a versão nova com backup e retorno automático se algo falhar. Sua biblioteca e suas configurações são mantidas.

**Privacidade:** sem análise de uso e sem rastreamento. O painel só fala com os serviços que você usa (Sakugabooru, GitHub, hosts das ferramentas, trace.moe e AniList).

**Licença:** gratuito para todos e **proibido vender ou cobrar** pelo Sakugaloader. Você pode usar no seu trabalho, inclusive pago para clientes e em vídeos monetizados. Os clipes pertencem aos seus donos e as ferramentas externas mantêm as próprias licenças.

Achou um erro? Abra uma [issue](https://github.com/wrdflap21-code/Sakuga-Upadate/issues) dizendo sua versão do After Effects e o que aconteceu.

</details>
