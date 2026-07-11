---
title: IHyperlinkManager
second_title: Aspose.Slides for Android via Java API Reference
description: Обеспечивает управление гиперссылками: добавление и удаление.
type: docs
url: /ru/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

Обеспечивает управление гиперссылками (добавление, удаление).

## Методы

| Метод | Описание |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Устанавливает внешнюю гиперссылку при щелчке. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Устанавливает внутреннюю гиперссылку при щелчке. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Удаляет гиперссылку при щелчке. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Устанавливает внешнюю гиперссылку при наведении мыши. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Устанавливает внутреннюю гиперслку при наведении мыши. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Удаляет гиперссылку при наведении мыши. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Устанавливает Macro гиперссылку при щелчке. |

### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

Устанавливает внешнюю гиперссылку при щелчке.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| url | java.lang.String | Hyperlink URL. |

**Возвращаемое значение:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)

### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Устанавливает внутреннюю гиперссылку при щелчке.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Целевой слайд. |

**Возвращаемое значение:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.

### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

Удаляет гиперссылку при щелчке.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

Устанавливает внешнюю гиперссылку при наведении мыши.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| url | java.lang.String | Hyperlink URL. |

**Возвращаемое значение:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.

### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Устанавливает внутреннюю гиперссылку при наведении мыши.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Целевой слайд. |

**Возвращаемое значение:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.

### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

Удаляет гиперссылку при наведении мыши.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

Устанавливает Macro гиперссылку при щелчке.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.BlankButton, 20, 20, 80, 30);
>      shape.getHyperlinkManager().setMacroHyperlinkClick("MacroName");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| macroName | java.lang.String | Имя макроса |

**Возвращаемое значение:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)