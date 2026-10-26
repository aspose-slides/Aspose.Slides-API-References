---
title: Write()
second_title: Αναφορά API Aspose.Slides για C++
description: Γράφει τη συγκεκριμένη μη υπογεγραμμένη 8-bit ακέραια τιμή στο ρεύμα εξόδου.
type: docs
weight: 92
url: /el/system.io/binarywriter/write/
---
## BinaryWriter::Write(uint8_t) μέθοδος

Γράφει τη συγκεκριμένη μη υπογεγραμμένη τιμή 8-bit ακέραιου στο ρεύμα εξόδου.

```cpp
virtual void System::IO::BinaryWriter::Write(uint8_t value)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | **uint8_t** | Η τιμή που θα γραφτεί |

## BinaryWriter::Write(const ArrayPtr\<uint8_t\>\&, int, int) μέθοδος

Γράφει το καθορισμένο υποσύνολο byte από τον καθορισμένο πίνακα byte στο ρεύμα εξόδου.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<uint8_t> &buffer, int index=0, int count=-1)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας που περιέχει τα byte που θα γραφτούν |
| index | int | Δείκτης βάσει 0 του στοιχείου στο **buffer** όπου αρχίζει το υποσύνολο προς εγγραφή |
| count | int | Ο αριθμός των στοιχείων στο υποσύνολο προς εγγραφή· -1 δηλώνει ότι το υποσύνολο λήγει όπου τελειώνει ο πίνακας **buffer** |

## BinaryWriter::Write(const ArrayPtr\<char_t\>\&, int, int) μέθοδος

Γράφει το καθορισμένο υποσύνολο χαρακτήρων UTF-16 από τον καθορισμένο πίνακα χαρακτήρων στο ρεύμα εξόδου.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<char_t> &buffer, int index=0, int count=-1)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Ο πίνακας που περιέχει τους χαρακτήρες που θα γραφτούν |
| index | int | Δείκτης βάσει 0 του στοιχείου στο **buffer** όπου αρχίζει το υποσύνολο προς εγγραφή |
| count | int | Ο αριθμός των χαρακτήρων στο υποσύνολο προς εγγραφή· -1 δηλώνει ότι το υποσύνολο λήγει όπου τελειώνει ο πίνακας **buffer** |

## BinaryWriter::Write(bool) μέθοδος

Γράφει ένα μόνο byte με τιμή 0 αν το **value** είναι 'true' και 1 αν το **value** είναι 'false' στο ρεύμα εξόδου.

```cpp
virtual void System::IO::BinaryWriter::Write(bool value)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | **bool** | Η λογική τιμή που καθορίζει την τιμή του byte που θα γραφτεί στο ρεύμα εξόδου |

## BinaryWriter::Write(char16_t) μέθοδος

Γράφει τον καθορισμένο 16-bit χαρακτήρα στο ρεύμα εξόδου.

```cpp
virtual void System::IO::BinaryWriter::Write(char16_t value)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char16_t | Η τιμή που θα γραφτεί |

## BinaryWriter::Write(int16_t) μέθοδος

Γράφει τη συγκεκριμένη 16-bit ακέραια τιμή στο ρεύμα εξόδου.

```cpp
virtual void System::IO::BinaryWriter::Write(int16_t value)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | **int16_t** | Η τιμή που θα γραφτεί |

## BinaryWriter::Write(int) μέθοδος

Γράφει τη συγκεκριμένη 32-bit ακέραια τιμή στο ρεύμα εξόδου.

```cpp
virtual void System::IO::BinaryWriter::Write(int value)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int | Η τιμή που θα γραφτεί |

## BinaryWriter::Write(int64_t) μέθοδος

Γράφει τη συγκεκριμένη 64-bit ακέραια τιμή στο ρεύμα εξόδου.

```cpp
virtual void System::IO::BinaryWriter::Write(int64_t value)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | **int64_t** | Η τιμή που θα γραφτεί |

## BinaryWriter::Write(uint16_t) μέθοδος

Γράφει τη συγκεκριμένη μη υπογεγραμμένη 16-bit ακέραια τιμή στο ρεύμα εξόδου.

```cpp
virtual void System::IO::BinaryWriter::Write(uint16_t value)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | **uint16_t** | Η τιμή που θα γραφτεί |

## BinaryWriter::Write(uint32_t) μέθοδος

Γράφει τη συγκεκριμένη μη υπογεγραμμένη 32-bit ακέραια τιμή στο ρεύμα εξόδου.

```cpp
virtual void System::IO::BinaryWriter::Write(uint32_t value)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | **uint32_t** | Η τιμή που θα γραφτεί |

## BinaryWriter::Write(uint64_t) μέθοδος

Γράφει τη συγκεκριμένη μη υπογεγραμμένη 64-bit ακέραια τιμή στο ρεύμα εξόδου.

```cpp
virtual void System::IO::BinaryWriter::Write(uint64_t value)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | **uint64_t** | Η τιμή που θα γραφτεί |

## BinaryWriter::Write(float) μέθοδος

Γράφει τη συγκεκριμένη τιμή μονής ακρίβειας τύπου float στο ρεύμα εξόδου.

```cpp
virtual void System::IO::BinaryWriter::Write(float value)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | **float** | Η τιμή που θα γραφτεί |

## BinaryWriter::Write(double) μέθοδος

Γράφει τη συγκεκριμένη τιμή διπλής ακρίβειας τύπου double στο ρεύμα εξόδου.

```cpp
virtual void System::IO::BinaryWriter::Write(double value)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | **double** | Η τιμή που θα γραφτεί |

## BinaryWriter::Write(const Decimal\&) μέθοδος

Γράφει την αναπαράσταση byte της καθορισμένης τιμής [Decimal](../../../system/decimal/) στο ρεύμα εξόδου.

```cpp
virtual void System::IO::BinaryWriter::Write(const Decimal &value)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [Decimal](../../../system/decimal/)\& | Η τιμή που θα γραφτεί |

## BinaryWriter::Write(const String\&) μέθοδος

Γράφει μια συμβολοσειρά με πρόθεμα μήκους στην τρέχουσα κωδικοποίηση στο ρεύμα εξόδου.

```cpp
virtual void System::IO::BinaryWriter::Write(const String &value)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Η συμβολοσειρά που θα γραφτεί |

## BinaryWriter::Write(const char_t *) μέθοδος

Γράφει μια συμβολοσειρά με πρόθεμα μήκους στην τρέχουσα κωδικοποίηση στο ρεύμα εξόδου.

```cpp
virtual void System::IO::BinaryWriter::Write(const char_t *value)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const char_t * | Η συμβολοσειρά C που θα γραφτεί |

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BinaryWriter](../)
* Class [Decimal](../../../system/decimal/)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)