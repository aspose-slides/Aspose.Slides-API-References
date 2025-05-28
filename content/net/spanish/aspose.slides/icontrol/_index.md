---
title: IControl
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa un control ActiveX.
type: docs
weight: 5430
url: /es/aspose.slides/icontrol/
---

## Interfaz IControl

Representa un control ActiveX.

```csharp
public interface IControl : ISlideComponent
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActiveXControlBinary](../../aspose.slides/icontrol/activexcontrolbinary) { get; } | Especifica la persistencia de un control ActiveX cuando el método utilizado para persistir es PersistStream, PersistStreamInit o PersistStorage. |
| [AsISlideComponent](../../aspose.slides/icontrol/asislidecomponent) { get; } | Permite obtener la interfaz base ISlideComponent. Solo lectura [`ISlideComponent`](../islidecomponent). |
| [ClassId](../../aspose.slides/icontrol/classid) { get; } | Obtiene el id de clase de este control. Solo lectura Guid. |
| [Frame](../../aspose.slides/icontrol/frame) { get; set; } | Devuelve o establece el marco del control. Lectura/escritura [`IShapeFrame`](../ishapeframe). |
| [Name](../../aspose.slides/icontrol/name) { get; set; } | Devuelve el nombre de este control. Lectura/escritura String. |
| [Persistence](../../aspose.slides/icontrol/persistence) { get; } | Obtiene el método utilizado para almacenar las propiedades del control ActiveX. Solo lectura [`PersistenceType`](../persistencetype). |
| [Properties](../../aspose.slides/icontrol/properties) { get; } | Devuelve una colección de propiedades ActiveX. Solo lectura [`IControlPropertiesCollection`](../icontrolpropertiescollection). |
| [SubstitutePictureFormat](../../aspose.slides/icontrol/substitutepictureformat) { get; } | Devuelve el objeto de propiedades de relleno de imagen de ControlEx. Solo lectura [`IPictureFillFormat`](../ipicturefillformat). |

### Ver También

* interfaz [ISlideComponent](../islidecomponent)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->