---
title: Presentation()
second_title: Aspose.Slides pro C++ API Reference
description: Tento konstruktor vytváří novou prezentaci od nuly. Vytvořená prezentace má jeden prázdný snímek.
type: docs
weight: 417
url: /cs/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() konstruktor

Tento konstruktor vytváří novou prezentaci od nuly. Vytvořená prezentace má jeden prázdný snímek.

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) konstruktor

Tento konstruktor vytváří novou prezentaci od nuly. Vytvořená prezentace má jeden prázdný snímek.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Další možnosti načítání. |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) konstruktor

Tento konstruktor je hlavním mechanismem pro načtení existujícího [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Vstupní proud. |

## Poznámky

```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) konstruktor

Tento konstruktor je hlavním mechanismem pro načtení existujícího [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Vstupní proud. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Další možnosti načítání. |

## Presentation::Presentation(System::String) konstruktor

Tento konstruktor získává cestu ke zdrojovému souboru, ze kterého jsou čteny obsah [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Vstupní soubor. |

## Poznámky

```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) konstruktor

Tento konstruktor získává cestu ke zdrojovému souboru, ze kterého jsou čteny obsah [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Vstupní soubor. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Další možnosti načítání. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Presentation](../)
* Třída [LoadOptions](../../loadoptions/)
* Třída [Stream](../../../system.io/stream/)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)