---
title: HyperlinkManager
second_title: Αναφορά API του Aspose.Slides για Java
description: Παρέχει διαχείριση υπερσυνδέσμων, προσθήκη και αφαίρεση.
type: docs
url: /el/com.aspose.slides/hyperlinkmanager/
---
**Κληρονομία:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

Παρέχει διαχείριση υπερσυνδέσμων (προσθήκη, αφαίρεση).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Ορίζει εξωτερικό υπερσύνδεσμο με κλικ. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Ορίζει εσωτερικό υπερσύνδεσμο με κλικ. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Αφαιρεί τον υπερσύνδεσμο με κλικ. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Ορίζει εξωτερικό υπερσύνδεσμο κατά το πέρασμα ποντικιού. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Ορίζει εσωτερικό υπερσύνδεσμο κατά το πέρασμα ποντικιού. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Αφαιρεί τον υπερσύνδεσμο κατά το πέρασμα ποντικιού. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Ορίζει υπερσύνδεσμο μακροεντολής με κλικ. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```

Ορίζει εξωτερικό υπερσύνδεσμο με κλικ.

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // Δημιουργεί μια κλάση Presentation που αντιπροσωπεύει ένα PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Αποκτά την πρώτη διαφάνεια στην παρουσίαση
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Προσθέτει ένα αντικείμενο AutoShape με τύπο ορισμένο ως Rectangle
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // Κάνει cast το shape σε AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // Προσπελάζει την ιδιότητα ITextFrame που σχετίζεται με το AutoShape
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Προσθέτει κάποιο κείμενο στο πλαίσιο
>      portion.setText("Aspose.Slides");
>      // Ορίζει το Hyperlink για το κείμενο του τμήματος
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // Αποθηκεύει την παρουσίαση PPTX
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | java.lang.String | URL του υπερσυνδέσμου. |

**Επιστρέφει:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Ορίζει εσωτερικό υπερσύνδεσμο με κλικ.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια-στόχος. |

**Επιστρέφει:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Υπερσύνδεσμος.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```

Αφαιρεί τον υπερσύνδεσμο με κλικ.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```

Ορίζει εξωτερικό υπερσύνδεσμο κατά το πέρασμα ποντικιού.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | java.lang.String | URL του υπερσυνδέσμου. |

**Επιστρέφει:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Υπερσύνδεσμος.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Ορίζει εσωτερικό υπερσύνδεσμο κατά το πέρασμα ποντικιού.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια-στόχος. |

**Επιστρέφει:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Υπερσύνδεσμος.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```

Αφαιρεί τον υπερσύνδεσμο κατά το πέρασμα ποντικιού.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```

Ορίζει υπερσύνδεσμο μακροεντολής με κλικ.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| macroName | java.lang.String | Όνομα της μακροεντολής |

**Επιστρέφει:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Αντικείμενο υπερσύνδεσμου [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject