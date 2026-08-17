---
title: IHyperlinkManager
second_title: Aspose.Slides for Java API Reference
description: Provide hyperlinks management adding removing.
type: docs
url: /el/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

Παρέχει διαχείριση υπερσυνδέσμων (προσθήκη, αφαίρεση).

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Ορίζει εξωτερικό υπερσύνδεσμο σε κλικ. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Ορίζει εσωτερικό υπερσύνδεσμο σε κλικ. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Αφαιρεί υπερσύνδεσμο σε κλικ. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Ορίζει εξωτερικό υπερσύνδεσμο κατά το πέρασμα του ποντικιού. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Ορίζει εσωτερικό υπερσύνδεσμο κατά το πέρασμα του ποντικιού. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Αφαιρεί υπερσύνδεσμο κατά το πέρασμα του ποντικιού. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Ορίζει υπερσύνδεσμο μακροεντολής σε κλικ. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

Ορίζει εξωτερικό υπερσύνδεσμο σε κλικ.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | java.lang.String | URL του υπερσυνδέσμου. |

**Τιμή επιστροφής:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Ορίζει εσωτερικό υπερσύνδεσμο σε κλικ.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Στόχος διαφάνειας. |

**Τιμή επιστροφής:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

Αφαιρεί υπερσύνδεσμο σε κλικ.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

Ορίζει εξωτερικό υπερσύνδεσμο κατά το πέρασμα του ποντικιού.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | java.lang.String | URL του υπερσυνδέσμου. |

**Τιμή επιστροφής:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Ορίζει εσωτερικό υπερσύνδεσμο κατά το πέρασμα του ποντικιού.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Στόχος διαφάνειας. |

**Τιμή επιστροφής:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

Αφαιρεί υπερσύνδεσμο κατά το πέρασμα του ποντικιού.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

Ορίζει υπερσύνδεσμο μακροεντολής σε κλικ.

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

**Τιμή επιστροφής:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)