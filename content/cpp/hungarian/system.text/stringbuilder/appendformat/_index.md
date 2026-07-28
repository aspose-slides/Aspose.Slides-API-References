---
title: AppendFormat()
second_title: Aspose.Slides C++ API Referencia
description: Formázott karakterláncot ad a builderhez.
type: docs
weight: 131
url: /hu/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String&, const TArgs&...) metódus


Formázott karakterláncot ad a builderhez.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TArgs | Argumentumok típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Formátum karakterlánc. |
| args | const TArgs\&... | Argumentumok a formátum karakterlánc helyeire beszúrásra. |

### Visszatérési érték

Ez a mutató.

## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>\&, const String&, const TArgs&...) metódus


Formázott karakterláncot ad a builderhez.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TArgs | Argumentumok típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)\<[IFormatProvider](../../../system/iformatprovider/)\>\& | Formátum szolgáltató; figyelmen kívül hagyva. |
| format | const [String](../../../system/string/)\& | Formátum karakterlánc. |
| args | const TArgs\&... | Argumentumok a formátum karakterlánc helyeire beszúrásra. |

### Visszatérési érték

Ez a mutató.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [IFormatProvider](../../../system/iformatprovider/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)