---
title: IColorOperationCollection
second_title: Aspose.Slides για Android μέσω Java API
description: Αντιπροσωπεύει μια συλλογή λειτουργιών μετασχηματισμού χρώματος.
type: docs
url: /el/com.aspose.slides/icoloroperationcollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

Αντιπροσωπεύει μια συλλογή λειτουργιών μετασχηματισμού χρώματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει ή ορίζει τη λειτουργία στη συγκεκριμένη θέση. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Επιστρέφει ή ορίζει τη λειτουργία στη συγκεκριμένη θέση. |
| [add(int operation, float parameter)](#add-int-float-) | Προσθέτει μια νέα λειτουργία στο τέλος της συλλογής. |
| [add(int operation)](#add-int-) | Προσθέτει μια νέα λειτουργία στο τέλος της συλλογής. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Εισάγει τη νέα λειτουργία σε μια συλλογή. |
| [insert(int position, int operation)](#insert-int-int-) | Εισάγει τη νέα λειτουργία σε μια συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί τη λειτουργία χρώματος από μια συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλες τις λειτουργίες χρώματος. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

Επιστρέφει ή ορίζει τη λειτουργία στη συγκεκριμένη θέση. Ανάγνωση/εγγραφή [IColorOperation](../../com.aspose.slides/icoloroperation).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```

Επιστρέφει ή ορίζει τη λειτουργία στη συγκεκριμένη θέση. Ανάγνωση/εγγραφή [IColorOperation](../../com.aspose.slides/icoloroperation).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```

Προσθέτει μια νέα λειτουργία στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| operation | int | Τύπος λειτουργίας. |
| parameter | float | Παράμετρος λειτουργίας. |

**Επιστρέφει:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Προστέθηκε η λειτουργία.
### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```

Προσθέτει μια νέα λειτουργία στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| operation | int | Τύπος λειτουργίας. |

**Επιστρέφει:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Προστέθηκε η λειτουργία.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```

Εισάγει τη νέα λειτουργία σε μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | int | Ο δείκτης όπου θα εισαχθεί η λειτουργία. |
| operation | int | Τύπος λειτουργίας. |
| parameter | float | Παράμετρος λειτουργίας. |

**Επιστρέφει:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Εισαχθείσα λειτουργία.
### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```

Εισάγει τη νέα λειτουργία σε μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | int | Ο δείκτης όπου θα εισαχθεί η λειτουργία. |
| operation | int | Τύπος λειτουργίας. |

**Επιστρέφει:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Εισαχθείσα λειτουργία.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί τη λειτουργία χρώματος από μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της λειτουργίας χρώματος για αφαίρεση. |

### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλες τις λειτουργίες χρώματος.