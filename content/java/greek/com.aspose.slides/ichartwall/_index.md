---
title: IChartWall
second_title: Aspose.Slides for Java API Reference
description: Αναπαριστά τους τοίχους σε 3d διαγράμματα.
type: docs
url: /el/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

Αναπαριστά τους τοίχους σε 3d διαγράμματα.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getThickness()](#getThickness--) | Επιστρέφει ή ορίζει το πάχος των τοίχων ως ποσοστό της μεγαλύτερης διάστασης του όγκου του διαγράμματος. |
| [setThickness(int value)](#setThickness-int-) | Επιστρέφει ή ορίζει το πάχος των τοίχων ως ποσοστό της μεγαλύτερης διάστασης του όγκου του διαγράμματος. |
| [getFormat()](#getFormat--) | Επιστρέφει τη διακόσμηση τοίχου, τη γραμμή, το εφέ, τα στυλ 3d. |
| [getPictureType()](#getPictureType--) | Επιστρέφει ή ορίζει τον τύπο της εικόνας. |
| [setPictureType(int value)](#setPictureType-int-) | Επιστρέφει ή ορίζει τον τύπο της εικόνας. |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```

Επιστρέφει ή ορίζει το πάχος των τοίχων ως ποσοστό της μεγαλύτερης διάστασης του όγκου του διαγράμματος. **Ανάγνωση/εγγραφή int.**

**Επιστρέφει:**
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```

Επιστρέφει ή ορίζει το πάχος των τοίχων ως ποσοστό της μεγαλύτερης διάστασης του όγκου του διαγράμματος. **Ανάγνωση/εγγραφή int.**

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Επιστρέφει τη διακόσμηση τοίχου, τη γραμμή, το εφέ, τα στυλ 3d. **Μόνο για ανάγνωση** [IFormat](../../com.aspose.slides/iformat).

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)
### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```

Επιστρέφει ή ορίζει τον τύπο της εικόνας. **Ανάγνωση/εγγραφή** [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Επιστρέφει:**
int
### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```

Επιστρέφει ή ορίζει τον τύπο της εικόνας. **Ανάγνωση/εγγραφή** [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |