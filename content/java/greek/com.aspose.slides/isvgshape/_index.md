---
title: ISvgShape
second_title: Aspose.Slides for Java API Reference
description: Αναπαριστά τις επιλογές για σχήμα SVG.
type: docs
url: /el/com.aspose.slides/isvgshape/
---```
public interface ISvgShape
```

Αναπαριστά τις επιλογές για σχήμα SVG.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setEventHandler(int eventType, String handler)](#setEventHandler-int-java.lang.String-) | Ορίζει διαχειριστή συμβάντος για το σχήμα |
| [getId()](#getId--) | Ορίζει ή λαμβάνει το id για το σχήμα |
| [setId(String value)](#setId-java.lang.String-) | Ορίζει ή λαμβάνει το id για το σχήμα |
### setEventHandler(int eventType, String handler) {#setEventHandler-int-java.lang.String-}
```
public abstract void setEventHandler(int eventType, String handler)
```

Ορίζει διαχειριστή συμβάντος για το σχήμα

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| eventType | int | Τύπος συμβάντος. |
| handler | java.lang.String | Συνάρτηση JavaScript για τη διαχείριση του συμβάντος. Η τιμή null αφαιρεί τον διαχειριστή. |

### getId() {#getId--}
```
public abstract String getId()
```

Ορίζει ή λαμβάνει το id για το σχήμα

**Επιστρέφει:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

Ορίζει ή λαμβάνει το id για το σχήμα

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |