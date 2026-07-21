---
title: GetPresentationText()
second_title: Справочник API Aspose.Slides для C++
description: Получает необработанный текст со слайдов
type: docs
weight: 53
url: /ru/aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) метод

Извлекает необработанный текст со слайдов

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Входной файл |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Режим извлечения |

### Return Value

Экземпляр [PresentationText](../../presentationtext/), содержащий массив SlideText, представляющий необработанный текст слайдов

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) метод

Извлекает необработанный текст со слайдов

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Входной поток |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Режим извлечения |

### Return Value

Экземпляр [PresentationText](../../presentationtext/), содержащий массив SlideText, представляющий необработанный текст слайдов

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) метод

Извлекает необработанный текст со слайдов

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Входной поток |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Режим извлечения |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Параметры загрузки |

### Return Value

Экземпляр [PresentationText](../../presentationtext/), содержащий массив SlideText, представляющий необработанный текст слайдов

## См. также

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IPresentationText](../../ipresentationtext/)
* Класс [String](../../../system/string/)
* Класс [PresentationFactory](../)
* Класс [Stream](../../../system.io/stream/)
* Класс [ILoadOptions](../../iloadoptions/)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)