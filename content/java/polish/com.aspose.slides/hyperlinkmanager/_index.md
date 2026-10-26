---
title: HyperlinkManager
second_title: Aspose.Slides dla Java – odniesienie API
description: Zapewnia zarządzanie hiperłączami, dodawanie i usuwanie.
type: docs
url: /pl/com.aspose.slides/hyperlinkmanager/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

Zarządzaj hiperłączami (dodawanie, usuwanie).
## Metody

| Metoda | Opis |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Ustaw zewnętrzny hiperłącze po kliknięciu. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Ustawia wewnętrzny hiperłącze po kliknięciu. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Usuwa hiperłącze po kliknięciu. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Ustawia zewnętrzny hiperłącze po najechaniu myszą. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Ustawia wewnętrzny hiperłącze po najechaniu myszą. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Usuwa hiperłącze po najechaniu myszą. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Ustaw hiperłącze makra po kliknięciu. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```

Ustawia zewnętrzny hiperłącze po kliknięciu.

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // Tworzy instancję klasy Presentation, która reprezentuje plik PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Pobiera pierwszy slajd w prezentacji
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Dodaje obiekt AutoShape z typem ustawionym na Rectangle
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // Rzutuje kształt na AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // Uzyskuje dostęp do właściwości ITextFrame powiązanej z AutoShape
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Dodaje tekst do ramki
>      portion.setText("Aspose.Slides");
>      // Ustawia hiperłącze dla tekstu części
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // Zapisuje prezentację PPTX
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| url | java.lang.String | Adres URL hiperłącza. |

**Zwraca:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Ustawia wewnętrzny hiperłącze po kliknięciu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Docelowy slajd. |

**Zwraca:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hiperłącze.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```

Usuwa hiperłącze po kliknięciu.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```

Ustawia zewnętrzny hiperłącze po najechaniu myszą.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| url | java.lang.String | Adres URL hiperłącza. |

**Zwraca:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hiperłącze.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Ustawia wewnętrzny hiperłącze po najechaniu myszą.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Docelowy slajd. |

**Zwraca:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hiperłącze.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```

Usuwa hiperłącze po najechaniu myszą.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```

Ustaw hiperłącze makra po kliknięciu.

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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| macroName | java.lang.String | Nazwa makra |

**Zwraca:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Obiekt Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject