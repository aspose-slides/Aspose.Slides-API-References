---
title: AppendFormat()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till formaterad sträng till byggaren.
type: docs
weight: 131
url: /sv/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String&, const TArgs&...) metod

Lägger till formaterad sträng till byggaren.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TArgs | Argumenttyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Formatsträng. |
| args | const TArgs\&... | Argument att infoga i formatsträngens positioner. |

### Returvärde

Denna pekare.

## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>\&, const String&, const TArgs\&...) metod

Lägger till formaterad sträng till byggaren.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TArgs | Argumenttyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)\<[IFormatProvider](../../../system/iformatprovider/)\>\& | Formatleverantör; ignoreras. |
| format | const [String](../../../system/string/)\& | Formatsträng. |
| args | const TArgs\&... | Argument att infoga i formatsträngens positioner. |

### Returvärde

Denna pekare.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [StringBuilder](../)
* Klass [String](../../../system/string/)
* Klass [IFormatProvider](../../../system/iformatprovider/)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)