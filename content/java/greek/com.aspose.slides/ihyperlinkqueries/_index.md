---
title: IHyperlinkQueries
second_title: Aspose.Slides for Java API Reference
description: Παρέχει εύκολη πρόσβαση στους ενσωματωμένους υπερσυνδέσμους.
type: docs
url: /el/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Παρέχει εύκολη πρόσβαση στους ενσωματωμένους υπερσυνδέσμους.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Λαμβάνει όλα τα υποαντικείμενα IHyperlinkContainer που περιέχουν μη μηδενικό HyperlinkClick. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Λαμβάνει όλα τα υποαντικείμενα IHyperlinkContainer που περιέχουν μη μηδενικό HyperlinkMouseOver. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Λαμβάνει όλα τα υποαντικείμενα IHyperlinkContainer που περιέχουν μη μηδενικό HyperlinkMouseOver. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Αφαιρεί όλους τους ενσωματωμένους υπερσυνδέσμους HyperlinkClick και HyperlinkMouseOver (σε όλα τα υποαντικείμενα IHyperlinkContainer). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```


Λαμβάνει όλα τα υποαντικείμενα IHyperlinkContainer που περιέχουν μη μηδενικό HyperlinkClick. Με το δεδομένο αντικείμενο IHyperlinkContainer μπορείτε να διαχειριστείτε τον υπερσύνδεσμό του (ανάγνωση, ενημέρωση ή κατάργηση). Δείτε τη διασύνδεση IHyperlinkContainer.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Όλα τα υποαντικείμενα IHyperlinkContainer που περιέχουν μη μηδενικό HyperlinkClick
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```


Λαμβάνει όλα τα υποαντικείμενα IHyperlinkContainer που περιέχουν μη μηδενικό HyperlinkMouseOver. Με το δεδομένο αντικείμενο IHyperlinkContainer μπορείτε να διαχειριστείτε τον υπερσύνδεσμό του (ανάγνωση, ενημέρωση ή κατάργηση). Δείτε τη διασύνδεση IHyperlinkContainer.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Όλα τα υποαντικείμενα IHyperlinkContainer που περιέχουν μη μηδενικό HyperlinkMouseOver
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```


Λαμβάνει όλα τα υποαντικείμενα IHyperlinkContainer που περιέχουν μη μηδενικό HyperlinkMouseOver. Με το δεδομένο αντικείμενο IHyperlinkContainer μπορείτε να διαχειριστείτε τον υπερσύνδεσμό του (ανάγνωση, ενημέρωση ή κατάργηση). Δείτε τη διασύνδεση IHyperlinkContainer.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Όλα τα υποαντικείμενα IHyperlinkContainer που περιέχουν μη μηδενικό HyperlinkMouseOver
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```


Αφαιρεί όλους τους ενσωματωμένους υπερσυνδέσμους HyperlinkClick και HyperlinkMouseOver (σε όλα τα υποαντικείμενα IHyperlinkContainer).