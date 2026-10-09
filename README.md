# SpiritFone

SpiritFone is a free Windows program for ITC / EVP research. It is free of
charge and will remain so.

## What is in this repository

| Item | Where |
|---|---|
| The SpiritFone Windows installer | the **Releases** page (right-hand side of this page) |
| Complete source code of the LSP Plugins version used by SpiritFone | `LSP-Plugins/lsp-plugins-src-1.2.35.tar.gz` |
| The one build file that differs from that source | `LSP-Plugins/plugins.mk.SpiritFone-build` |
| Licence texts and notice | `LSP-Plugins/COPYING.LESSER.txt`, `LSP-Plugins/COPYING.txt`, `LSP-Plugins/NOTICE.txt`, `DeepFilterNet/LICENSE-MIT` |

The source code of SpiritFone itself is not in this repository.

## Third-party software and licences

SpiritFone includes, or works with, the software below. All names and
trademarks belong to their owners.

**LSP Plugins (included).** The Multiband Expander and Multiband Compressor in
the Vocal Lift card come from LSP Plugins version 1.2.35 by the Linux Studio
Plugins Project, built unmodified for Windows 64-bit into `lsp-plugins.dll`
(only the list of plug-ins to build was shortened). LSP Plugins is licensed
under the GNU Lesser General Public License version 3 (LGPLv3). The complete
source code is in this repository's `LSP-Plugins` folder; the licence texts
and the build file are also installed with SpiritFone. SpiritFone loads `lsp-plugins.dll` from
its own folder, and you may replace it with your own build that provides the
same two plug-ins. https://lsp-plug.in/ , https://github.com/lsp-plugins/

**Voxengo SPAN (included).** SPAN.dll is copyright Voxengo (Aleksey Vaneev).
It is redistributed unmodified with Voxengo's written permission, on the
condition that SpiritFone remains free of charge. The permission is installed
with SpiritFone. https://www.voxengo.com/product/span/

**DeepFilterNet (included).** DeepFilterNet by Hendrik Schroeter, with its
stock model, is used for voice extraction. It is dual-licensed under the
MIT License or the Apache License 2.0, at the user's option. SpiritFone uses
it under the MIT License; the licence text, with the copyright notice
"Copyright (c) 2021 Hendrik Schröter", is in the `DeepFilterNet` folder of this
repository and is installed with SpiritFone.
https://github.com/Rikorose/DeepFilterNet

**Cockos ReaFIR and ReaEQ (NOT included, downloaded at install).** The ReaPlugs
licence does not allow redistribution, so SpiritFone does not contain them.
ReaFIR is required for SpiritFone to work properly (ReaEQ is optional). The
SpiritFone installer offers to download Cockos' own 64-bit ReaPlugs installer
from reaper.fm and runs it normally, so you install it under Cockos' own
terms. https://www.reaper.fm/reaplugs/

## Where to get SpiritFone

Go to the **Releases** page of this repository and download
`SpiritFone-Setup-0.1.0.exe`. Run it and follow the installer.

## Credits

This work is based upon the foundational work of the following pioneers in the field of ITC research: Konstantin Raudive, Friedrich Jürgenson, Anabela Cardoso and others. A limitless amount of credit must also be given to those who followed those pioneers; Ron & Lourdes Yacovetti and Tony & Cherie Rathman, for without them, this project would not exist. Thank you.
