---
title: ToType()
second_title: Referencia de API de Aspose.Slides para C++
description: "Convierte el valor de esta instancia a un System::Object del System::Type especificado que tiene un valor equivalente, utilizando la información de formato específica de la cultura."
type: docs
weight: 209
url: /es/system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) método

Convierte el valor de esta instancia a un [System::Object](../../object/) del System::Type especificado que tiene un valor equivalente, utilizando la información de formato específica de la cultura.

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | El System::Type al que se convierte el valor de esta instancia. |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Una implementación de la interfaz [System::IFormatProvider](../../iformatprovider/) que proporciona información de formato específica de la cultura. |

### Valor devuelto

Una instancia de [System::Object](../../object/) del tipo conversionType cuyo valor es equivalente al valor de esta instancia.

## Véase también

* Typedef [SharedPtr](../../sharedptr/)
* Clase [Object](../../object/)
* Clase [TypeInfo](../../typeinfo/)
* Clase [IFormatProvider](../../iformatprovider/)
* Clase [IConvertible](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)