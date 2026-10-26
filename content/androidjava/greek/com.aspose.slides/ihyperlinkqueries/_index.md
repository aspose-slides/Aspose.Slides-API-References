---
title: IHyperlinkQueries
second_title: Aspose.Slides for Android via Java API Reference
description: Παρέχει εύκολη πρόσβαση στα ενσωματωμένα υπερσυνδέσμους.
type: docs
url: /el/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Παρέχει εύκολη πρόσβαση στα ενσωματωμένα υπερσυνδέσμους.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Λαμβάνει όλα τα υπο-αντικείμενα IHyperlinkContainer που περιέχουν μη μηδενικό HyperlinkClick. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Λαμβάνει όλα τα υπο-αντικείμενα IHyperlinkContainer που περιέχουν μη μηδενικό HyperlinkMouseOver. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Λαμβάνει όλα τα υπο-αντικείμενα IHyperlinkContainer που περιέχουν μη μηδενικό HyperlinkMouseOver. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Αφαιρεί όλα τα ενσωματωμένα υπερσυνδέσμους HyperlinkClick και HyperlinkMouseOver (σε όλα τα υπο-αντικείμενα IHyperlinkContainer). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

Λαμβάνει όλα τα υπο-αντικείμενα IHyperlinkContainer που περιέχουν μη μηδενικό HyperlinkClick. Με το δοσμένο αντικείμενο IHyperlinkContainer μπορείτε να διαχειριστείτε το υπερσύνδεσμο του (ανάγνωση, ενημέρωση ή διαγραφή). Δείτε την IHyperlinkContainer διεπαφή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Όλα τα υπο-αντικείμενα IHyperlinkContainer που περιέχουν μη μηδενικό HyperlinkClick
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

Λαμβάνει όλα τα υπο-αντικείμενα IHyperlinkContainer που περιέχουν μη μηδενικό HyperlinkMouseOver. Με το δοσμένο αντικείμενο IHyperlinkContainer μπορείτε να διαχειριστείτε το υπερσύνδεσμο του (ανάγνωση, ενημέρωση ή διαγραφή). Δείτε την IHyperlinkContainer διεπαφή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Όλα τα υπο-αντικείμενα IHyperlinkContainer που περιέχουν μη μηδενικό HyperlinkMouseOver
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

Λαμβάνει όλα τα υπο-αντικείμενα IHyperlinkContainer που περιέχουν μη μηδενικό HyperlinkMouseOver. Με το δοσμένο αντικείμενο IHyperlinkContainer μπορείτε να διαχειριστείτε το υπερσύνδεσμο του (ανάγνωση, ενημέρωση ή διαγραφή). Δείτε την IHyperlinkContainer διεπαφή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Όλα τα υπο-αντικείμενα IHyperlinkContainer που περιέχουν μη μηδενικό HyperlinkMouseOver
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

Αφαιρεί όλα τα ενσωματωμένα υπερσυνδέσμους HyperlinkClick και HyperlinkMouseOver (σε όλα τα υπο-αντικείμενα IHyperlinkContainer).