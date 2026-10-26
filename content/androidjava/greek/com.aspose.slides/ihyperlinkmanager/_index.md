---
title: IHyperlinkManager
second_title: Aspose.Slides for Android via Java API Reference
description: Παρέχει διαχείριση υπερσυνδέσμων (προσθήκη, αφαίρεση).
type: docs
url: /el/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

Παρέχει διαχείριση υπερσυνδέσμων (προσθήκη, αφαίρεση).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Ορίζει εξωτερικό υπερσύνδεσμο στο κλικ. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Ορίζει εσωτερικό υπερσύνδεσμο στο κλικ. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Αφαιρεί τον υπερσύνδεσμο στο κλικ. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Ορίζει εξωτερικό υπερσύνδεσμο όταν περνάει το ποντίκι. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Ορίζει εσωτερικό υπερσύνδεσμο όταν περνάει το ποντίκι. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Αφαιρεί τον υπερσύνδεσμο όταν περνάει το ποντίκι. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Ορίζει υπερσύνδεσμο μακροεντολής στο κλικ. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```


Ορίζει εξωτερικό υπερσύνδεσμο στο κλικ.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL του υπερσυνδέσμου. |

**Τιμή επιστροφής:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - αντικείμενο Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```


Ορίζει εσωτερικό υπερσύνδεσμο στο κλικ.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Διάφάνεια-στόχος. |

**Τιμή επιστροφής:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```


Αφαιρεί τον υπερσύνδεσμο στο κλικ.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```


Ορίζει εξωτερικό υπερσύνδεσμο όταν περνάει το ποντίκι.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL του υπερσυνδέσμου. |

**Τιμή επιστροφής:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```


Ορίζει εσωτερικό υπερσύνδεσμο όταν περνάει το ποντίκι.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Διάφάνεια-στόχος. |

**Τιμή επιστροφής:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```


Αφαιρεί τον υπερσύνδεσμο όταν περνάει το ποντίκι.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
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

**Τιμή επιστροφής:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - αντικείμενο Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)