---
title: IHyperlinkManager
second_title: Aspose.Slides for Java API Reference
description: Обеспечивает управление гиперссылками (добавление, удаление).
type: docs
url: /ru/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

Обеспечивает управление гиперссылками (добавление, удаление).
## Методы

| Метод | Описание |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Set external hyperlink on click. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Sets internal hyperlink on click. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Removes hyperlink on click. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Sets external hyperlink mouse over. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Sets internal hyperlink mouse over. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Removes hyperlink mouse over. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Set Macro hyperlink on a click. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

Установить внешнюю гиперссылку при клике.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| url | java.lang.String | URL гиперссылки. |

**Возвращаемое значение:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Устанавливает внутреннюю гиперссылку при клике.

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

Удаляет гиперссылку при клике.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

Устанавливает внешнюю гиперссылку при наведении мыши.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| url | java.lang.String | URL гиперссылки. |

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

Установить гиперссылку макроса при клике.

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