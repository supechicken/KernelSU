[English](README.md) | **Asante Twi** | [Español](README_ES.md) | [简体中文](README_CN.md) | [繁體中文](README_TW.md) | [日本語](README_JP.md) | [한국어](README_KR.md) | [Polski](README_PL.md) | [Português (Brasil)](README_PT-BR.md) | [Türkçe](README_TR.md) | [Русский](README_RU.md) | [Tiếng Việt](README_VI.md) | [Indonesia](README_ID.md) | [עברית](README_IW.md) | [हिंदी](README_IN.md) | [Italiano](README_IT.md)

# KernelSU

<img src="https://kernelsu.org/logo.png" style="width: 96px;" alt="logo">

Kernel-based root solutions a wɔayɛ ama Android mfidie ahorow

[![Latest release](https://img.shields.io/github/v/release/tiann/KernelSU?label=Release&logo=github)](https://github.com/tiann/KernelSU/releases/latest)
[![Weblate](https://img.shields.io/badge/Localization-Weblate-teal?logo=weblate)](https://hosted.weblate.org/engage/kernelsu)
[![Channel](https://img.shields.io/badge/Follow-Telegram-blue.svg?logo=telegram)](https://t.me/KernelSU)
[![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-orange.svg?logo=gnu)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
[![GitHub License](https://img.shields.io/github/license/tiann/KernelSU?logo=gnu)](/LICENSE)

## KernelSU ho Su

1. Ɛma wo `superuser` ne root-based access ɛwɔ kernel no so.
2. Module ho nhyehyɛe a egyina [metamodules](https://kernelsu.org/guide/metamodule.html) so: Eyi tumi ma woyɛ nsakrae aberɛ a wonfa wonsa ɛnka system no.
3. [App Profile](https://kernelsu.org/guide/app-profile.html): Fa root tumi no sie.

## Mfidie a KernelSU tumi yɛ adwuma wɔ so

KernelSU bɔ adwuma yie paa wɔ mfidie a ekura Android GKI 2.0 (kernel 5.10+). Kernel adada (4.14+) bi so wɔ hɔ a KernelSU yɛ adwuma wɔ so. Nanso sɛ wopɛ no saa (wɔ 4.14 no so a), ɛsɛsɛ woankasa yɛ wo kernel compilation.

Ne saa nti, WSA, ChromeOS, ɛne container-based Android nyinaa tumi de KernelSU di dwuma .

Sesiara no, `arm64-v8a` ne `x86_64` architecture nkoa na etumi fa.

> [!AWHƐYIE]

> Kernel versions a ɛreba nansa yi no de nsakrae soronko bi a ɛsɛe project yi dwumadie na ɛma KernelSU edi nkuguo. Eyi betumi akanyan `kernel panic` wɔ `x86_64` mfidie so! Hwɛ wɛbsaet no so na woanya nsɛm pii!!

## Sɛnea yɛde di dwuma

- [Sɛnea yɛ instɔle](https://kernelsu.org/guide/installation.html)
- [Sɛ wopɛsɛ wo buildi wɔ wo machine so a](https://kernelsu.org/guide/how-to-build.html)
- [Official website](https://kernelsu.org/)

## Kasa nkyerɛaseɛ

Sɛnea ɛbɛyɛ a yɛbɛboa ma wɔakyerɛ KernelSU ase akɔ kasa foforɔ mu no, yɛrengye nkyerɛase ntoboa nfa Weblate so bio. Mprempren yi, yɛde LLM ahorow na edi nkyerɛase nyinaa ho dwuma.

Sɛ wopɛ sɛ woboa ma yɛ yɛ nkyerɛaseɛ ma kasa foforo a, ntwentwɛn wo nan ase sɛ wubebue PR. Yɛsrɛ, monhyɛ no nsow sɛ yɛrengye nsakrae a wobɛyɛ wɔ Engiresi ne China nkyerɛase a ɛwɔ hɔ dedaw no mu ntum.

## Nkitahodie

- Telegram: [@KernelSU](https://t.me/KernelSU)

## Project ho ahobanbɔ

Sɛ wopɛ nsɛm a ɛfa amanneɛbɔ a ɛfa ahobanbɔ ho mmerɛwyɛ ho wɔ KernelSU mu a, hwɛ [SECURITY.md](/SECURITY.md) fael no.

## Project yi ho tumi nkrataa

- Faels a ɛwɔ `kernel` directory no mu no nyinaa yɛ [GPL-2.0-pɛ](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html).
- Afã afoforo nyinaa a ɛwɔ project yi mu, gye `kernel` directory no pɛ, yɛ [GPL-3.0-anaa-n'abadiakyire](https://www.gnu.org/licenses/gpl-3.0.html).

## Ndaase nkɔ mma

- [Kernel-Assisted Superuser](https://git.zx2c4.com/kernel-assisted-superuser/about/): KernelSU project adwen no.
- [Magisk](https://github.com/topjohnwu/Magisk): Root tool kokroko a tumi wom'.
- [genuine](https://github.com/brevent/genuine/): APK v2 signatures a w'agye atum.
- [Diamorphine](https://github.com/m0nad/Diamorphine): Rootkitskills ho nneɛma bi ho nimdeɛ.
