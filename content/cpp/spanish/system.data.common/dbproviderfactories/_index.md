---
title: DbProviderFactories
second_title: Referencia de API de Aspose.Slides para C++
description: "API para obtener fábricas de proveedores de DB. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 53
url: /es/system.data.common/dbproviderfactories/
---
## DbProviderFactories clase

API para obtener fábricas de proveedores de DB. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class DbProviderFactories
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[DbProviderFactory](../dbproviderfactory/)\> [GetFactory](./getfactory/)(const [String](../../system/string/)\&) | Obtiene la fábrica del proveedor DB por nombre. |
## Ver también

* Espacio de nombres [System::Data::Common](../)
* Biblioteca [Aspose.Slides](../../)