---
title: IBulkTextFormattable
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an object with possibility of bulk setting child text elements formats.
type: docs
url: /ru/com.aspose.slides/ibulktextformattable/
---```
public interface IBulkTextFormattable
```

Представляет объект, позволяющий массово задавать форматы дочерних текстовых элементов.
## Методы

| Метод | Описание |
| --- | --- |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Sets defined portion format properties to all element's portions. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Sets defined paragraph format properties to all element's paragraphs. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Sets defined text frame format properties to all element's text frames. |
### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setTextFormat(IPortionFormat source)
```

Устанавливает определённые свойства формата фрагмента для всех фрагментов элемента.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat object with necessary properties set. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public abstract void setTextFormat(IParagraphFormat source)
```

Устанавливает определённые свойства формата абзаца для всех абзацев элемента.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat object with necessary properties set. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public abstract void setTextFormat(ITextFrameFormat source)
```

Устанавливает определённые свойства формата текстового кадра для всех текстовых кадров элемента.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat object with necessary properties set. |