---
title: Control
second_title: Referencia de API de Aspose.Slidес para .NET
description: Representa un control ActiveX.
type: docs
weight: 2600
url: /es/aspose.slides/control/
---

## Clase Control

Representa un control ActiveX.

```csharp
public class Control : DomObject<ControlCollection>, IControl
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActiveXControlBinary](../../aspose.slides/control/activexcontrolbinary) { get; } | Especifica la persistencia de un control ActiveX cuando el método utilizado para persistir es PersistStream, PersistStreamInit o PersistStorage. |
| [ClassId](../../aspose.slides/control/classid) { get; set; } | Obtiene el id de clase de este control. Solo lectura Guid. |
| [Frame](../../aspose.slides/control/frame) { get; set; } | Devuelve o establece el marco del control. Lectura/escritura [`IShapeFrame`](../ishapeframe). |
| [Name](../../aspose.slides/control/name) { get; set; } | Obtiene o establece el nombre de este control. Lectura/escritura String. |
| [Persistence](../../aspose.slides/control/persistence) { get; } | Obtiene el método utilizado para almacenar propiedades del control ActiveX. Solo lectura [`PersistenceType`](../persistencetype). |
| [Properties](../../aspose.slides/control/properties) { get; } | Devuelve una colección de propiedades de ActiveX. Nota: Aspose.Slides solo admite propiedades de ActiveX basadas en XML. Si las propiedades se almacenan en formato binario, esta propiedad devolverá nulo. Solo lectura [`IControlPropertiesCollection`](../icontrolpropertiescollection). |
| [SubstitutePictureFormat](../../aspose.slides/control/substitutepictureformat) { get; } | Devuelve el objeto de propiedades de relleno de imagen del Control. Solo lectura [`IPictureFillFormat`](../ipicturefillformat). |

### Ver también

* clase [DomObject&lt;TParent&gt;](../domobject-1)
* clase [ControlCollection](../controlcollection)
* interfaz [IControl](../icontrol)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->