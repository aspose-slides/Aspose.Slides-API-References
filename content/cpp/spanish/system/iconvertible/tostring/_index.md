---
title: ToString()
second_title: Referencia de API de Aspose.Slides para C++
description: "Convierte el valor de esta instancia en un System::String equivalente usando la información de formato específica de la cultura especificada."
type: docs
weight: 196
url: /es/system/iconvertible/tostring/
---
## IConvertible::ToString(System::SharedPtr\<System::IFormatProvider\>) método

Convierte el valor de esta instancia a un equivalente [System::String](../../string/) utilizando la información de formato específica de la cultura especificada.

```cpp
virtual System::String System::IConvertible::ToString(System::SharedPtr<System::IFormatProvider> provider)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Una implementación de la interfaz [System::IFormatProvider](../../iformatprovider/) que proporciona información de formato específica de la cultura. |

### Valor de retorno

Una instancia [System::String](../../string/) equivalente al valor de esta instancia.

## IConvertible::ToString() const método

Analogía del método [Object.ToString()](../../object/tostring/) de C#. Permite convertir objetos personalizados a string.

```cpp
virtual String System::Object::ToString() const
```

### Valor de retorno

Representación [String](../../string/) tal como la proporciona la clase final.

## Véase también

* Typedef [SharedPtr](../../sharedptr/)
* Clase [String](../../string/)
* Clase [IFormatProvider](../../iformatprovider/)
* Clase [IConvertible](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)