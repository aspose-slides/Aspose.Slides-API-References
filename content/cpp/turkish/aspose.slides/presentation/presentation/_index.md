---
title: Presentation()
second_title: Aspose.Slides for C++ API Referansı
description: Bu yapıcı sıfırdan yeni bir sunum oluşturur. Oluşturulan sunumda bir boş slayt bulunur.
type: docs
weight: 417
url: /tr/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() yapıcı

Bu yapıcı, sıfırdan yeni bir sunum oluşturur. Oluşturulan sunumda bir boş slayt bulunur.

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) yapıcı

Bu yapıcı, sıfırdan yeni bir sunum oluşturur. Oluşturulan sunumda bir boş slayt bulunur.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Ek yükleme seçenekleri. |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) yapıcı

Bu yapıcı, mevcut bir [Presentation](../) okumanın birincil mekanizmasıdır.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Giriş akışı. |

## Açıklamalar

```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) yapıcı

Bu yapıcı, mevcut bir [Presentation](../) okumanın birincil mekanizmasıdır.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Giriş akışı. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Ek yükleme seçenekleri. |

## Presentation::Presentation(System::String) yapıcı

Bu yapıcı, [Presentation](../)'nin içeriğinin okunduğu kaynak dosya yolunu alır.

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Giriş dosyası. |

## Açıklamalar

```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) yapıcı

Bu yapıcı, [Presentation](../)'nin içeriğinin okunduğu kaynak dosya yolunu alır.

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Giriş dosyası. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Ek yükleme seçenekleri. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Presentation](../)
* Sınıf [LoadOptions](../../loadoptions/)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [String](../../../system/string/)
* Ad alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)