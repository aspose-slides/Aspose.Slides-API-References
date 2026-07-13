---
title: HyperlinkManager
second_title: Aspose.Slides dla Androida poprzez odwołanie do API Java
description: Zapewnia zarządzanie hiperłączami, ich dodawanie i usuwanie.
type: docs
url: /pl/com.aspose.slides/hyperlinkmanager/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

Zarządzaj hiperłączami (dodawanie, usuwanie).
## Metody

| Metoda | Opis |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Ustaw zewnętrzny hiperlink po kliknięciu. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Ustawia wewnętrzny hiperlink po kliknięciu. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Usuwa hiperlink po kliknięciu. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Ustawia zewnętrzny hiperlink po najechaniu myszą. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Ustawia wewnętrzny hiperlink po najechaniu myszą. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Usuwa hiperlink po najechaniu myszą. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Ustaw hiperlink makra po kliknięciu. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```


Ustaw zewnętrzny hiperlink po kliknięciu.

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // Tworzy instancję klasy Presentation reprezentującej plik PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Pobiera pierwszy slajd w prezentacji
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Dodaje obiekt AutoShape o typie ustawionym jako Rectangle
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // Rzutuje kształt na AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // Uzyskuje dostęp do właściwości ITextFrame powiązanej z AutoShape
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Dodaje trochę tekstu do ramki
>      portion.setText("Aspose.Slides");
>      // Ustawia hiperłącze dla tekstu fragmentu
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
| url | java.lang.String | Adres URL hiperlinku. |

**Zwraca:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```


Ustawia wewnętrzny hiperlink po kliknięciu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Docelowy slajd. |

**Zwraca:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```


Usuwa hiperlink po kliknięciu.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```


Ustawia zewnętrzny hiperlink po najechaniu myszą.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| url | java.lang.String | Adres URL hiperlinku. |

**Zwraca:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```


Ustawia wewnętrzny hiperlink po najechaniu myszą.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Docelowy slajd. |

**Zwraca:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```


Usuwa hiperlink po najechaniu myszą.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```


Ustaw hiperlink makra po kliknięciu.

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
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject