---
title: Presentation()
second_title: Riferimento API di Aspose.Slides per C++
description: Questo costruttore crea una nuova presentazione da zero. La presentazione creata contiene una diapositiva vuota.
type: docs
weight: 417
url: /it/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() costruttore

Questo costruttore crea una nuova presentazione da zero. La presentazione creata contiene una diapositiva vuota.

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) costruttore

Questo costruttore crea una nuova presentazione da zero. La presentazione creata contiene una diapositiva vuota.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Opzioni di caricamento aggiuntive. |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) costruttore

Questo costruttore è il meccanismo principale per leggere un [Presentation](../) esistente.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flusso di input. |

## Osservazioni

```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) costruttore

Questo costruttore è il meccanismo principale per leggere un [Presentation](../) esistente.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flusso di input. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Opzioni di caricamento aggiuntive. |

## Presentation::Presentation(System::String) costruttore

Questo costruttore ottiene il percorso del file sorgente da cui vengono letti i contenuti del [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | File di input. |

## Osservazioni

```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) costruttore

Questo costruttore ottiene il percorso del file sorgente da cui vengono letti i contenuti del [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | File di input. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Opzioni di caricamento aggiuntive. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../)
* Class [LoadOptions](../../loadoptions/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)