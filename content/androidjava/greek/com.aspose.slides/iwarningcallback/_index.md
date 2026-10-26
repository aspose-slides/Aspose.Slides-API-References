---
title: IWarningCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Interface for classes which receive warning
type: docs
url: /el/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Διεπαφή για κλάσεις που λαμβάνουν προειδοποίηση
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Μέθοδος επιστροφής κλήσης που λαμβάνει προειδοποίηση και αποφασίζει εάν η λειτουργία πρέπει να τερματιστεί. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

Μέθοδος επιστροφής κλήσης που λαμβάνει προειδοποίηση και αποφασίζει εάν η λειτουργία πρέπει να τερματιστεί.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | Προειδοποίηση προς επεξεργασία. |

**Επιστρέφει:**
int - Απόφαση τερματισμού [ReturnAction](../../com.aspose.slides/returnaction).