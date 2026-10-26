---
title: HyperlinkManager
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Παρέχει διαχείριση υπερσυνδέσμων, προσθήκη και αφαίρεση.
type: docs
url: /el/com.aspose.slides/hyperlinkmanager/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Εφαρμοσμένες Διεπαφές:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

Παρέχετε διαχείριση υπερσυνδέσμων (προσθήκη, αφαίρεση).
## Μέθοδοι

| Method | Description |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Ορίζει εξωτερικό υπερσύνδεσμο στο κλικ. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Ορίζει εσωτερικό υπερσύνδεσμο στο κλικ. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Αφαιρεί υπερσύνδεσμο στο κλικ. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Ορίζει εξωτερικό υπερσύνδεσμο όταν ο δείκτης είναι πάνω. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Ορίζει εσωτερικό υπερσύνδεσμο όταν ο δείκτης είναι πάνω. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Αφαιρεί υπερσύνδεσμο όταν ο δείκτης είναι πάνω. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Ορίζει υπερσύνδεσμο μακροεντολής στο κλικ. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```

Ορίζει εξωτερικό υπερσύνδεσμο στο κλικ.

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // Δημιουργεί μια κλάση Presentation που αντιπροσωπεύει ένα PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Λαμβάνει την πρώτη διαφάνεια στην παρουσίαση
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Προσθέτει ένα αντικείμενο AutoShape με τύπο Ορθογώνιο
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // Μετατρέπει το σχήμα σε AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // Προσπελαύνει την ιδιότητα ITextFrame που σχετίζεται με το AutoShape
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Προσθέτει κείμενο στο πλαίσιο
>      portion.setText("Aspose.Slides");
>      // Ορίζει τον υπερσύνδεσμο για το κείμενο της περιοχής
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // Αποθηκεύει την παρουσίαση PPTX
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL του υπερσυνδέσμου. |

**Τιμές Επιστροφής:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Ορίζει εσωτερικό υπερσύνδεσμο στο κλικ.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια-στόχος. |

**Τιμές Επιστροφής:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```

Αφαιρεί υπερσύνδεσμο στο κλικ.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```

Ορίζει εξωτερικό υπερσύνδεσμο όταν ο δείκτης είναι πάνω.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL του υπερσυνδέσμου. |

**Τιμές Επιστροφής:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Ορίζει εσωτερικό υπερσύνδεσμο όταν ο δείκτης είναι πάνω.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια-στόχος. |

**Τιμές Επιστροφής:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```

Αφαιρεί υπερσύνδεσμο όταν ο δείκτης είναι πάνω.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```

Ορίζει υπερσύνδεσμο μακροεντολής στο κλικ.

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


**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| macroName | java.lang.String | Όνομα της μακροεντολής |

**Τιμές Επιστροφής:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Τιμές Επιστροφής:**
com.aspose.slides.IDOMObject