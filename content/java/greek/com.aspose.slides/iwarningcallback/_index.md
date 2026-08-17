---
title: IWarningCallback
second_title: Aspose.Slides for Java API Reference
description: Interface for classes which receive warning
type: docs
url: /el/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Διεπαφή για κλάσεις που λαμβάνουν προειδοποίηση
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Μέθοδος κλήσης η οποία λαμβάνει προειδοποίηση και αποφασίζει αν πρέπει να διακοπεί η λειτουργία. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```


Μέθοδος κλήσης η οποία λαμβάνει προειδοποίηση και αποφασίζει αν πρέπει να διακοπεί η λειτουργία.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | Προειδοποίηση προς επεξεργασία. |

**Επιστρέφει:**
int - Απόφαση διακοπής [ReturnAction](../../com.aspose.slides/returnaction).