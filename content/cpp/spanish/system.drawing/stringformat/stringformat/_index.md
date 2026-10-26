---
title: StringFormat()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una nueva instancia de la clase StringFormat.
type: docs
weight: 1
url: /es/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() constructor

Construye una nueva instancia de la clase [StringFormat](../).

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) constructor

Construye una nueva instancia de la clase [StringFormat](../) con las banderas de formato y el idioma especificados.

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | Una combinación bit a bit del valor enum StringFormatFlags que especifica el formato de cadena que será representado por el objeto que se está creando |
| language | **int32_t** | Un idioma del texto |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) constructor

Constructor de copia.

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | Un objeto [StringFormat](../) del cual copiar |

## Ver también

* Enum [StringFormatFlags](../../stringformatflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringFormat](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)