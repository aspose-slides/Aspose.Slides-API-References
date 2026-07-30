---
title: Hyperlink()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un'istanza di un hyperlink.
type: docs
weight: 339
url: /it/aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) costruttore


Crea un'istanza di un hyperlink.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL. |

## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) costruttore


Crea un'istanza di un hyperlink che punta a una slide specifica. Nota: l'hyperlink creato deve essere assegnato a qualche oggetto della stessa presentazione, altrimenti il collegamento verrà salvato come NoAction.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Diapositiva di destinazione. |

## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) costruttore


Crea un'istanza di un hyperlink usando un altro hyperlink come sorgente, sovrascrivendo le proprietà secondarie.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | hyperlink di origine |
| targetFrame | [System::String](../../../system/string/) | Frame di destinazione |
| tooltip | [System::String](../../../system/string/) | Testo tooltip |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Hyperlink](../)
* Classe [ISlide](../../islide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)