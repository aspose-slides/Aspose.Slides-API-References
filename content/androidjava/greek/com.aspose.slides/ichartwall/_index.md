---
title: IChartWall
second_title: Aspose.Slides for Android via Java API Reference
description: Represents walls on 3d charts.
type: docs
url: /el/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

Αντιπροσωπεύει τα τοίχια σε 3δ διαγράμματα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getThickness()](#getThickness--) | Επιστρέφει ή ορίζει το πάχος των τοίχων ως ποσοστό της μεγαλύτερης διάστασης του όγκου του διαγράμματος. |
| [setThickness(int value)](#setThickness-int-) | Επιστρέφει ή ορίζει το πάχος των τοίχων ως ποσοστό της μεγαλύτερης διάστασης του όγκου του διαγράμματος. |
| [getFormat()](#getFormat--) | Επιστρέφει τη γέμιση, τη γραμμή, το εφέ, τα 3δ στυλ του τοίχου. |
| [getPictureType()](#getPictureType--) | Επιστρέφει ή ορίζει τον τύπο εικόνας. |
| [setPictureType(int value)](#setPictureType-int-) | Επιστρέφει ή ορίζει τον τύπο εικόνας. |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```


Επιστρέφει ή ορίζει το πάχος των τοίχων ως ποσοστό της μεγαλύτερης διάστασης του όγκου του διαγράμματος. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```


Επιστρέφει ή ορίζει το πάχος των τοίχων ως ποσοστό της μεγαλύτερης διάστασης του όγκου του διαγράμματος. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Επιστρέφει τη γέμιση, τη γραμμή, το εφέ, τα 3δ στυλ του τοίχου. Μόνο για ανάγνωση [IFormat](../../com.aspose.slides/iformat).

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)
### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```


Επιστρέφει ή ορίζει τον τύπο εικόνας. Ανάγνωση/εγγραφή [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Επιστρέφει:**
int
### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```


Επιστρέφει ή ορίζει τον τύπο εικόνας. Ανάγνωση/εγγραφή [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |