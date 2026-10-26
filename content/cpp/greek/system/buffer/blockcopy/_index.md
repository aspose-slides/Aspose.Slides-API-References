---
title: BlockCopy()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντιγράφει έναν καθορισμένο αριθμό byte από τον πηγαίο buffer στον προορισμό buffer.
type: docs
weight: 1
url: /el/system/buffer/blockcopy/
---
## Buffer::BlockCopy(const uint8_t *, int, uint8_t *, int, int) μέθοδος

Αντιγράφει έναν καθορισμένο αριθμό byte από τον πηγαίο buffer στον προορισμό buffer.

```cpp
static void System::Buffer::BlockCopy(const uint8_t *src, int srcOffset, uint8_t *dst, int dstOffset, int count)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| src | const **uint8_t** * | Δείκτης στο πηγαίο buffer |
| srcOffset | int | Μετατόπιση byte στο πηγαίο buffer όπου αρχίζει η αντιγραφή |
| dst | **uint8_t** * | Δείκτης στον προορισμό buffer |
| dstOffset | int | Μετατόπιση byte στον προορισμό buffer όπου ξεκινά η εισαγωγή δεδομένων |
| count | int | Αριθμός byte προς αντιγραφή |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) μέθοδος

Αντιλαμβάνεται δύο καθορισμένους τύπους αραιών ως ακατέργαστα arrays byte και αντιγράφει δεδομένα από το ένα στο άλλο.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TSrc | Ο τύπος των στοιχείων του πηγαίου array |
| TDst | Ο τύπος των στοιχείων του προορισματικού array |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Το πηγαίο array |
| srcOffset | int | Μετατόπιση byte στο πηγαίο array όπου αρχίζει η αντιγραφή |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Το προορισματικό array |
| dstOffset | int | Μετατόπιση byte στο προορισματικό array όπου ξεκινά η εισαγωγή δεδομένων |
| count | int | Αριθμός byte προς αντιγραφή |

## Buffer::BlockCopy(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) μέθοδος

Αντιλαμβάνεται δύο καθορισμένους πίνακες ως ακατέργαστα arrays byte και αντιγράφει δεδομένα από το ένα στο άλλο.

```cpp
static void System::Buffer::BlockCopy(const SharedPtr<ArrayBase> &src, int srcOffset, const SharedPtr<ArrayBase> &dst, int dstOffset, int count)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | Το πηγαίο array |
| srcOffset | int | Μετατόπιση byte στο πηγαίο array όπου αρχίζει η αντιγραφή |
| dst | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | Το προορισματικό array |
| dstOffset | int | Μετατόπιση byte στο προορισματικό array όπου ξεκινά η εισαγωγή δεδομένων |
| count | int | Αριθμός byte προς αντιγραφή |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) μέθοδος

Αντιλαμβάνεται δύο καθορισμένους τύπους αραιών ως ακατέργαστα arrays byte και αντιγράφει δεδομένα από το ένα στο άλλο.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TSrc | Ο τύπος των στοιχείων της πηγαίας προβολής array |
| TDst | Ο τύπος των στοιχείων της προορισματικής προβολής array |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | Η πηγαία προβολή array |
| srcOffset | int | Μετατόπιση byte στην πηγαία προβολή array όπου αρχίζει η αντιγραφή |
| dst | const System::Details::ArrayView\<TDst\>\& | Η προορισματική προβολή array |
| dstOffset | int | Μετατόπιση byte στην προορισματική προβολή array όπου ξεκινά η εισαγωγή δεδομένων |
| count | int | Αριθμός byte προς αντιγραφή |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) μέθοδος

Αντιλαμβάνεται δύο καθορισμένους τύπους αραιών ως ακατέργαστα arrays byte και αντιγράφει δεδομένα από το ένα στο άλλο.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TSrc | Ο τύπος των στοιχείων του πηγαίου array |
| TDst | Ο τύπος των στοιχείων της προορισματικής προβολής array |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Το πηγαίο array |
| srcOffset | int | Μετατόπιση byte στο πηγαίο array όπου αρχίζει η αντιγραφή |
| dst | const System::Details::ArrayView\<TDst\>\& | Η προορισματική προβολή array |
| dstOffset | int | Μετατόπιση byte στην προορισματική προβολή array όπου ξεκινά η εισαγωγή δεδομένων |
| count | int | Αριθμός byte προς αντιγραφή |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) μέθοδος

Αντιλαμβάνεται δύο καθορισμένους τύπους αραιών ως ακατέργαστα arrays byte και αντιγράφει δεδομένα από το ένα στο άλλο.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TSrc | Ο τύπος των στοιχείων της πηγαίας προβολής array |
| TDst | Ο τύπος των στοιχείων του προορισματικού array |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | Η πηγαία προβολή array |
| srcOffset | int | Μετατόπιση byte στην πηγαία προβολή array όπου αρχίζει η αντιγραφή |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Το προορισματικό array |
| dstOffset | int | Μετατόπιση byte στο προορισματικό array όπου ξεκινά η εισαγωγή δεδομένων |
| count | int | Αριθμός byte προς αντιγραφή |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) μέθοδος

Αντιλαμβάνεται δύο καθορισμένους τύπους αραιών ως ακατέργαστα arrays byte και αντιγράφει δεδομένα από το ένα στο άλλο.

```cpp
template<typename TSrc,std::size_t,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TSrc | Ο τύπος των στοιχείων του πηγαίου στοίβας array |
| NS | Το μέγεθος του πηγαίου στοίβας array |
| TDst | Ο τύπος των στοιχείων του προορισματικού στοίβας array |
| ND | Το μέγεθος του προορισματικού στοίβας array |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | Η πηγαία στοίβα array |
| srcOffset | int | Μετατόπιση byte στην πηγαία στοίβα array όπου αρχίζει η αντιγραφή |
| dst | const System::Details::StackArray\<TDst, ND\>\& | Η προορισματική στοίβα array |
| dstOffset | int | Μετατόπιση byte στην προορισματική στοίβα array όπου ξεκινά η εισαγωγή δεδομένων |
| count | int | Αριθμός byte προς αντιγραφή |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) μέθοδος

Αντιλαμβάνεται δύο καθορισμένους τύπους αραιών ως ακατέργαστα arrays byte και αντιγράφει δεδομένα από το ένα στο άλλο.

```cpp
template<typename TSrc,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TSrc | Ο τύπος των στοιχείων του πηγαίου array |
| TDst | Ο τύπος των στοιχείων του προορισματικού στοίβας array |
| ND | Το μέγεθος του προορισματικού στοίβας array |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Το πηγαίο array |
| srcOffset | int | Μετατόπιση byte στο πηγαίο array όπου αρχίζει η αντιγραφή |
| dst | const System::Details::StackArray\<TDst, ND\>\& | Η προορισματική στοίβα array |
| dstOffset | int | Μετατόπιση byte στην προορισματική στοίβα array όπου ξεκινά η εισαγωγή δεδομένων |
| count | int | Αριθμός byte προς αντιγραφή |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) μέθοδος

Αντιλαμβάνεται δύο καθορισμένους τύπους αραιών ως ακατέργαστα arrays byte και αντιγράφει δεδομένα από το ένα στο άλλο.

```cpp
template<typename TSrc,std::size_t,typename TDst> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TSrc | Ο τύπος των στοιχείων της πηγαίας στοίβας array |
| NS | Το μέγεθος της πηγαίας στοίβας array |
| TDst | Ο τύπος των στοιχείων του προορισματικού array |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | Η πηγαία στοίβα array |
| srcOffset | int | Μετατόπιση byte στην πηγαία στοίβα array όπου αρχίζει η αντιγραφή |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Το προορισματικό array |
| dstOffset | int | Μετατόπιση byte στο προορισματικό array όπου ξεκινά η εισαγωγή δεδομένων |
| count | int | Αριθμός byte προς αντιγραφή |

## Δείτε επίσης

* Τύπος [SharedPtr](../../sharedptr/)
* Κλάση [Buffer](../)
* Κλάση [Array](../../array/)
* Κλάση [ArrayBase](../../arraybase/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)