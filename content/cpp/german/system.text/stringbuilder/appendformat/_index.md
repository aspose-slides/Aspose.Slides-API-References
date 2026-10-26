---
title: AppendFormat()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt formatierte Zeichenfolge zum Builder hinzu.
type: docs
weight: 131
url: /de/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String\&, const TArgs\&...) method

Fügt formatierte Zeichenfolge zum Builder hinzu.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TArgs | Argumenttyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Formatzeichenfolge. |
| args | const TArgs\&... | Argumente, die an den Positionen der Formatzeichenfolge eingefügt werden. |

### Rückgabewert

Dieser Zeiger.

## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>\&, const String\&, const TArgs\&...) method

Fügt formatierte Zeichenfolge zum Builder hinzu.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TArgs | Argumenttyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)\<[IFormatProvider](../../../system/iformatprovider/)\>\& | Formatprovider; wird ignoriert. |
| format | const [String](../../../system/string/)\& | Formatzeichenfolge. |
| args | const TArgs\&... | Argumente, die an den Positionen der Formatzeichenfolge eingefügt werden. |

### Rückgabewert

Dieser Zeiger.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [StringBuilder](../)
* Klasse [String](../../../system/string/)
* Klasse [IFormatProvider](../../../system/iformatprovider/)
* Namensraum [System::Text](../../)
* Bibliothek [Aspose.Slides](../../../)