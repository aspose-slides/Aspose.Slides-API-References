---
title: HyperlinkManager
second_title: Aspose.Slides для Android через справочник Java API
description: Обеспечивает управление гиперссылками: добавление и удаление.
type: docs
url: /ru/com.aspose.slides/hyperlinkmanager/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

Обеспечивает управление гиперссылками (добавление, удаление).
## Методы

| Метод | Описание |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Устанавливает внешнюю гиперссылку при щелчке. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Устанавливает внутреннюю гиперссылку при щелчке. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Удаляет гиперссылку при щелчке. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Устанавливает внешнюю гиперссылку при наведении мыши. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Устанавливает внутреннюю гиперссылку при наведении мыши. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Удаляет гиперссылку при наведении мыши. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Устанавливает гиперссылку на макрос при щелчке. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```

Устанавливает внешнюю гиперссылка при щелчке.

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // Создает экземпляр класса Presentation, представляющего PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Получает первый слайд в презентации
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Добавляет объект AutoShape с типом Rectangle
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // Приводит форму к типу AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // Получает доступ к свойству ITextFrame, связанному с AutoShape
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Добавляет некоторый текст в фрейм
>      portion.setText("Aspose.Slides");
>      // Устанавливает гиперссылку для текста части
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // Сохраняет PPTX-презентацию
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| url | java.lang.String | URL гиперссылки. |

**Возвращаемое значение:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Устанавливает внутреннюю гиперссылку при щелчке.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Целевой слайд. |

**Возвращаемое значение:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Гиперссылка.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```

Удаляет гиперссылку при щелчке.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```

Устанавливает внешнюю гиперссылку при наведении мыши.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| url | java.lang.String | URL гиперссылки. |

**Возвращаемое значение:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Гиперссылка.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Устанавливает внутреннюю гиперссылку при наведении мыши.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Целевой слайд. |

**Возвращаемое значение:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Гиперссылка.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```

Удаляет гиперссылку при наведении мыши.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```

Устанавливает гиперссылку на макрос при щелчке.

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
[IHyperlink](../../com.aspose.slides/ihyperlink) - Объект гиперссылки [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject