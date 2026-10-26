---
title: Presentation()
second_title: Aspose.Slides C++ API referenciája
description: Ez a konstruktor új prezentációt hoz létre a semmiből. A létrehozott prezentáció egy üres diát tartalmaz.
type: docs
weight: 417
url: /hu/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() konstruktor

Ez a konstruktor új prezentációt hoz létre a semmiből. A létrehozott prezentáció egy üres diát tartalmaz.

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) konstruktor

Ez a konstruktor új prezentációt hoz létre a semmiből. A létrehozott prezentáció egy üres diát tartalmaz.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | További betöltési beállítások. |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) konstruktor

Ez a konstruktor az elsődleges mechanizmus egy meglévő [Presentation](../) beolvasásához.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Bemeneti adatfolyam. |

## Megjegyzések

```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) konstruktor

Ez a konstruktor az elsődleges mechanizmus egy meglévő [Presentation](../) beolvasásához.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Bemeneti adatfolyam. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | További betöltési beállítások. |

## Presentation::Presentation(System::String) konstruktor

Ez a konstruktor megkapja a forrásfájl elérési útját, amelyről a [Presentation](../) tartalma beolvasásra kerül.

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Bemeneti fájl. |

## Megjegyzések

```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) konstruktor

Ez a konstruktor megkapja a forrásfájl elérési útját, amelyről a [Presentation](../) tartalma beolvasásra kerül.

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Bemeneti fájl. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | További betöltési beállítások. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Presentation](../)
* Osztály [LoadOptions](../../loadoptions/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)