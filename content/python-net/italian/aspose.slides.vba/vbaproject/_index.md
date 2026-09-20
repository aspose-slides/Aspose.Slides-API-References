---
title: VbaProject class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.vba/vbaproject/
---
## VbaProject classe

Rappresenta il progetto VBA con macro di presentazione.

Il tipo VbaProject espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides.vba/vbaproject/__init__/#) | Questo costruttore crea un nuovo progetto VBA da zero.<br/>            Il progetto sarà creato nella codepage 1252 Windows Latin 1 (ANSI) |
| [`__init__(self, data)`](/slides/python-net/it/aspose.slides.vba/vbaproject/__init__/#bytes) | Questo costruttore carica il progetto VBA dalla rappresentazione binaria del contenitore OLE. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`name`](/slides/python-net/it/aspose.slides.vba/vbaproject/name/) | Restituisce il nome del progetto VBA.<br/>            Sola lettura **str**. |
| [`modules`](/slides/python-net/it/aspose.slides.vba/vbaproject/modules/) | Restituisce l'elenco di tutti i moduli contenuti nel progetto VBA.<br/>            Sola lettura [`IVbaModuleCollection`](/slides/python-net/it/aspose.slides.vba/ivbamodulecollection). |
| [`references`](/slides/python-net/it/aspose.slides.vba/vbaproject/references/) | Restituisce l'elenco di tutti i riferimenti contenuti nel progetto VBA.<br/>            Sola lettura [`IVbaReferenceCollection`](/slides/python-net/it/aspose.slides.vba/ivbareferencecollection). |
| [`is_password_protected`](/slides/python-net/it/aspose.slides.vba/vbaproject/is_password_protected/) | Indica se il VBAProject è protetto da una password per visualizzare le proprietà del progetto.<br/>            Sola lettura **bool**. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`to_binary(self)`](/slides/python-net/it/aspose.slides.vba/vbaproject/to_binary/#) | Restituisce la rappresentazione binaria del progetto VBA come contenitore OLE |


### Vedi anche
* modulo [`aspose.slides.vba`](/slides/python-net/it/aspose.slides.vba)
* libreria [`Aspose.Slides`](/slides/python-net)