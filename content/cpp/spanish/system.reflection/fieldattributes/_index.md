---
title: FieldAttributes
second_title: Referencia de API de Aspose.Slides para C++
description: Atributos de campo reflejados.
type: docs
weight: 170
url: /es/system.reflection/fieldattributes/
---
## FieldAttributes enumeración

Atributos de campo reflejados.

```cpp
enum class FieldAttributes
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| FieldAccessMask | 7 | Máscara de acceso a miembros. Use esta máscara para obtener información de accesibilidad. |
| PrivateScope | 0 | Miembros no referenciables. |
| Private | 1 | Miembros privados. |
| FamANDAssem | 2 | Miembros privados y con alcance de ensamblado. |
| Assembly | 3 | Miembros con alcance de ensamblado. |
| Family | 4 | Miembros accesibles por el tipo y subtipos. |
| FamORAssem | 5 | Miembros accesibles por el tipo, subtipos y ensamblado. |
| Public | 6 | Miembros accesibles por cualquiera. |
| Static | 16 | Miembros estáticos a diferencia de los miembros de instancia. |
| InitOnly | 32 | Miembros const que solo pueden inicializarse pero no modificarse. |
| Literal | 64 | Miembros constantes en tiempo de compilación. |
| NotSerialized | 128 | Miembros no serializados. |
| SpecialName | 512 | Campo especial con uno de los nombres siguientes. |
| PinvokeImpl | 8192 | Implementación interop dirigida. |
| ReservedMask | 38144 | Banderas reservadas solo para uso en tiempo de ejecución. |
| RTSpecialName | 1024 | El tiempo de ejecución debería comprobar la codificación del nombre. |
| HasFieldMarshal | 4096 | Hay información de marshaling presente. |
| HasDefault | 32768 | Hay valor predeterminado presente. |
| HasFieldRVA | 256 | Hay RVA presente. |

## Ver también

* Espacio de nombres [System::Reflection](../)
* Biblioteca [Aspose.Slides](../../)