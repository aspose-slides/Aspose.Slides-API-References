---
title: IWarningInfo
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αντιπροσωπεύει μια βασική διεπαφή για όλες τις προειδοποιήσεις.
type: docs
url: /el/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Αντιπροσωπεύει μια βασική διεπαφή για όλες τις προειδοποιήσεις.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | Εάν το receiver δεν είναι null, τερματίζει την προειδοποίηση σε έναν καθορισμένο παραλήπτη και ρίχνει την AbortRequestedException εάν το receiver αποφάσισε να ακυρώσει μια λειτουργία. |
| [getWarningType()](#getWarningType--) | Επιστρέφει έναν τύπο προειδοποίησης. |
| [getDescription()](#getDescription--) | Επιστρέφει μια ανθρώπινα αναγνώσιμη περιγραφή αυτής της προειδοποίησης. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

Εάν το receiver δεν είναι null, τερματίζει την προειδοποίηση σε έναν καθορισμένο παραλήπτη και ρίχνει την AbortRequestedException εάν το receiver αποφάσισε να ακυρώσει μια λειτουργία.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Αντικείμενο παραλήπτη [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

Επιστρέφει έναν τύπο προειδ

ώ

σης. Μόνο-για-ανάγνωση [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Επιστρέφει:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

Επιστρέφει μια ανθρώπινα αναγνώσιμη περιγραφή αυτής της προειδοποίησης. Μόνο-για-ανάγνωση String.

**Επιστρέφει:**
java.lang.String