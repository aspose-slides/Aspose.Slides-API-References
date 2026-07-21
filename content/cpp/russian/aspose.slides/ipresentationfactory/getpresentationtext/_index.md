---
title: GetPresentationText()
second_title: Справочник API Aspose.Slides для C++
description: Получает необработанный текст со слайдов
type: docs
weight: 40
url: /ru/aspose.slides/ipresentationfactory/getpresentationtext/
---
## IPresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) method


Получает необработанный текст со слайдов

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Входной файл |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Режим извлечения |

### Возвращаемое значение

Экземпляр [PresentationText](../../presentationtext/) содержащий массив SlideText, представляющий необработанный текст слайдов

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) method


Получает необработанный текст со слайдов

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Входной поток |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Режим извлечения |

### Возвращаемое значение

Экземпляр [PresentationText](../../presentationtext/) содержащий массив SlideText, представляющий необработанный текст слайдов

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) method


Получает необработанный текст со слайдов

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Входной поток |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Режим извлечения |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Параметры загрузки |

### Возвращаемое значение

Экземпляр [PresentationText](../../presentationtext/) содержащий массив SlideText, представляющий необработанный текст слайдов

## См. также

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationText](../../ipresentationtext/)
* Class [String](../../../system/string/)
* Class [IPresentationFactory](../)
* Class [Stream](../../../system.io/stream/)
* Class [ILoadOptions](../../iloadoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)