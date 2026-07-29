---
title: IsNullOrEmpty()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar om samlingen är null eller tom.
type: docs
weight: 27
url: /sv/system/testtools/isnullarempty/
---
## TestTools::IsNullOrEmpty(const SharedPtr\<T\>\&) method


Kontrollerar om samlingen är null eller tom.

```cpp
template<typename T> static bool System::TestTools::IsNullOrEmpty(const SharedPtr<T> &collection)
```


### Mallparametrar

| Parameter | Description |
| --- | --- |
| T | Typ av samling. |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Samling att kontrollera. |

### Returvärde

Sant om samlingen är null eller har noll element, annars falskt.

## TestTools::IsNullOrEmpty(const System::String\&) method


Kontrollerar om strängen är null eller tom.

```cpp
static bool System::TestTools::IsNullOrEmpty(const System::String &str)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) att kontrollera. |

### Returvärde

Sant om strängen är null eller har noll längd, annars falskt.

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Struct [TestTools](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)