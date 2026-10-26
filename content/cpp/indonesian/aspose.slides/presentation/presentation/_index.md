---
title: Presentation()
second_title: Referensi API Aspose.Slides untuk C++
description: Konstruktor ini membuat presentasi baru dari awal. Presentasi yang dibuat memiliki satu slide kosong.
type: docs
weight: 417
url: /id/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() konstruktor

Konstruktor ini membuat presentasi baru dari awal. Presentasi yang dibuat memiliki satu slide kosong.

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) konstruktor

Konstruktor ini membuat presentasi baru dari awal. Presentasi yang dibuat memiliki satu slide kosong.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Opsi pemuatan tambahan. |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) konstruktor

Konstruktor ini adalah mekanisme utama untuk membaca [Presentation](../) yang ada.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream masukan. |

## Catatan

```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) konstruktor

Konstruktor ini adalah mekanisme utama untuk membaca [Presentation](../) yang ada.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream masukan. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Opsi pemuatan tambahan. |

## Presentation::Presentation(System::String) konstruktor

Konstruktor ini memperoleh jalur berkas sumber dari mana isi [Presentation](../) dibaca.

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Berkas masukan. |

## Catatan

```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) konstruktor

Konstruktor ini memperoleh jalur berkas sumber dari mana isi [Presentation](../) dibaca.

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Berkas masukan. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Opsi pemuatan tambahan. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../)
* Class [LoadOptions](../../loadoptions/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)