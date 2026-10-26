---
title: Compare()
second_title: Aspose.Slides C++ API hivatkozás
description: Kisebb-egyenlő-nagyobb összehasonlít két részkarakterláncot.
type: docs
weight: 820
url: /hu/system/string/compare/
---
## String::Compare(const String\&, int, const String\&, int, int, bool) method

Kisebb-egyenlő-nagyobb összehasonlít két részkarakterláncot.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Az első karakterlánc a összehasonlításhoz. |
| indexA | int | Az első karakterlánc részstringjének kezdete. |
| strB | const [String](../)\& | A második karakterlánc a összehasonlításhoz. |
| indexB | int | A második karakterlánc részstringjének kezdete. |
| length | int | Az összehasonlítandó karakterek száma. |
| ignoreCase | **bool** | Megadja, hogy az összehasonlítás kis- és nagybetűérzékeny-e. |

### Return Value

Negatív érték, ha az első részkarakterlánc kisebb a másodiknál, nulla, ha egyeznek, különben pozitív érték.

## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) method

Kisebb-egyenlő-nagyobb összehasonlít két részkarakterláncot.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Az első karakterlánc a összehasonlításhoz. |
| indexA | int | Az első karakterlánc részstringjének kezdete. |
| strB | const [String](../)\& | A második karakterlánc a összehasonlításhoz. |
| indexB | int | A második karakterlánc részstringjének kezdete. |
| length | int | Az összehasonlítandó karakterek száma. |
| ignoreCase | **bool** | Megadja, hogy az összehasonlítás kis- és nagybetűérzékeny-e. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Az összehasonlításhoz használandó kultúra. |

### Return Value

Negatív érték, ha az első részkarakterlánc kisebb a másodiknál, nulla, ha egyeznek, különben pozitív érték.

## String::Compare(const String\&, const String\&, System::StringComparison) method

Kisebb-egyenlő-nagyobb összehasonlít két karakterláncot.

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Az első karakterlánc a összehasonlításhoz. |
| strB | const [String](../)\& | A második karakterlánc a összehasonlításhoz. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mód. |

### Return Value

Negatív érték, ha az első részkarakterlánc kisebb a másodiknál, nulla, ha egyeznek, különben pozitív érték.

## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) method

Kisebb-egyenlő-nagyobb összehasonlít két karakterláncot.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Az első karakterlánc a összehasonlításhoz. |
| indexA | int | Az első karakterlánc részstringjének kezdete. |
| strB | const [String](../)\& | A második karakterlánc a összehasonlításhoz. |
| indexB | int | A második karakterlánc részstringjének kezdete. |
| length | int | Az összehasonlítandó karakterek száma. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mód. |

### Return Value

Negatív érték, ha az első részkarakterlánc kisebb a másodiknál, nulla, ha egyeznek, különben pozitív érték.

## String::Compare(const String\&, const String\&, bool) method

Kisebb-egyenlő-nagyobb összehasonlít két karakterláncot.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Az első karakterlánc a összehasonlításhoz. |
| strB | const [String](../)\& | A második karakterlánc a összehasonlításhoz. |
| ignoreCase | **bool** | Megadja, hogy az összehasonlítás kis- és nagybetűérzékeny-e. |

### Return Value

Negatív érték, ha az első részkarakterlánc kisebb a másodiknál, nulla, ha egyeznek, különben pozitív érték.

## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) method

Kisebb-egyenlő-nagyobb összehasonlít két karakterláncot.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Az első karakterlánc a összehasonlításhoz. |
| strB | const [String](../)\& | A második karakterlánc a összehasonlításhoz. |
| ignoreCase | **bool** | Megadja, hogy az összehasonlítás kis- és nagybetűérzékeny-e. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Az összehasonlításhoz használandó kultúra. |

### Return Value

Negatív érték, ha az első részkarakterlánc kisebb a másodiknál, nulla, ha egyeznek, különben pozitív érték.

## See Also

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)