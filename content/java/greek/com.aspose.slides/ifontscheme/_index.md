---
title: IFontScheme
second_title: Aspose.Slides for Java API Reference
description: Αποθηκεύει γραμματοσειρές που ορίζονται από το θέμα.
type: docs
url: /el/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

Αποθηκεύει γραμματοσειρές που ορίζονται από το θέμα.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getMinor()](#getMinor--) | Επιστρέφει τη συλλογή γραμματοσειρών για το τμήμα "body" της διαφάνειας. |
| [getMajor()](#getMajor--) | Επιστρέφει τη συλλογή γραμματοσειρών για το τμήμα "heading" της διαφάνειας. |
| [getName()](#getName--) | Επιστρέφει το όνομα του σχήματος γραμματοσειράς. |
| [setName(String value)](#setName-java.lang.String-) | Επιστρέφει το όνομα του σχήματος γραμματοσειράς. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```


Επιστρέφει τη συλλογή γραμματοσειρών για το τμήμα "body" της διαφάνειας. Μόνο-ανάγνωση [IFonts](../../com.aspose.slides/ifonts).

**Επιστρέφει:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```


Επιστρέφει τη συλλογή γραμματοσειρών για το τμήμα "heading" της διαφάνειας. Μόνο-ανάγνωση [IFonts](../../com.aspose.slides/ifonts).

**Επιστρέφει:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```


Επιστρέφει το όνομα του σχήματος γραμματοσειράς. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Επιστρέφει το όνομα του σχήματος γραμματοσειράς. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |