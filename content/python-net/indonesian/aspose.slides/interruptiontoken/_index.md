---
title: InterruptionToken class
second_title: Referensi API Aspose.Slides untuk Python melalui .NET
description: 
type: docs
url: /id/aspose.slides/interruptiontoken/
---
## InterruptionToken kelas

Kelas ini mewakili token yang digunakan untuk memberi sinyal pada tugas yang berjalan lama apakah interupsi diminta.

Tipe InterruptionToken mengekspos anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`none`](/slides/python-net/id/aspose.slides/interruptiontoken/none/) | Mewakili token interupsi kosong.<br/>            Operasi yang berjalan lama tidak akan pernah diinterupsi melalui [`InterruptionTokenSource.interrupt`](/slides/python-net/id/aspose.slides/interruptiontokensource/interrupt)<br/>            saat menggunakan token ini. |
| [`is_interruption_requested`](/slides/python-net/id/aspose.slides/interruptiontoken/is_interruption_requested/) | Mengembalikan **bool**.true jika interupsi diminta. |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`throw_if_interruption_requested(self)`](/slides/python-net/id/aspose.slides/interruptiontoken/throw_if_interruption_requested/#) | Melempar OperationCanceledException jika<br/>            interupsi diminta. |


### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)