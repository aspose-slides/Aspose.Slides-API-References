---
title: AppendFormat()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrega una cadena formateada al constructor.
type: docs
weight: 131
url: /es/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String&, const TArgs&...) método

Agrega una cadena formateada al constructor.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TArgs | Tipo de los argumentos. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Cadena de formato. |
| args | const TArgs\&... | Argumentos para insertar en las posiciones de la cadena de formato. |

### Valor de retorno

Este puntero.

## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>\&, const String&, const TArgs&...) método

Agrega una cadena formateada al constructor.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TArgs | Tipo de los argumentos. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)\<[IFormatProvider](../../../system/iformatprovider/)\>\& | Proveedor de formato; ignorado. |
| format | const [String](../../../system/string/)\& | Cadena de formato. |
| args | const TArgs\&... | Argumentos para insertar en las posiciones de la cadena de formato. |

### Valor de retorno

Este puntero.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [StringBuilder](../)
* Clase [String](../../../system/string/)
* Clase [IFormatProvider](../../../system/iformatprovider/)
* Espacio de nombres [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)