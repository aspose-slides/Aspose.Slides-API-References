---
title: PresentationLockingBehavior
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa el comportamiento respecto al tratamiento delIPresentation./ipresentation fuente archivo o Stream  mientras carga y trabaja con una instancia deIPresentation./ipresentationLa fuente es el parámetro que se pasa alIPresentation./ipresentation constructor. En el ejemplo a continuación la fuente es el archivo pres.pptx
type: docs
weight: 8910
url: /es/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enumeration

Representa el comportamiento respecto al tratamiento del[`IPresentation`](../ipresentation) fuente (archivo o Stream ) mientras carga y trabaja con una instancia de[`IPresentation`](../ipresentation)La fuente es el parámetro que se pasa al[`IPresentation`](../ipresentation) constructor. En el ejemplo a continuación, la fuente es el archivo "pres.pptx":

```csharp
LoadOptions loadOptions = new LoadOptions { 
  BlobManagementOptions = { PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked } };
using (IPresentation pres = new Presentation("pres.pptx", loadOptions)) { }
```

Para este ejemplo, la fuente (archivo "pres.pptx") se bloqueará durante un[`IPresentation`](../ipresentation) vida útil de la instancia, es decir, el otro proceso no puede modificarla ni eliminarla.

```csharp
public enum PresentationLockingBehavior
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| LoadAndRelease | `0` | La fuente se bloqueará solo por un tiempo de[`IPresentation`](../ipresentation) ejecución del constructor.  Si[`IsTemporaryFilesAllowed`](../iblobmanagementoptions/istemporaryfilesallowed) se establece en falso, todos los BLOB se cargarán en la memoria. De lo contrario, se pueden utilizar otros medios, como archivos temporales. Este comportamiento es más lento queKeepLocked , y si es posible pasar la propiedad de la fuente a[`IPresentation`](../ipresentation) , se recomienda utilizarKeepLocked . |
| KeepLocked | `1` | La fuente se bloqueará durante toda la vida de[`IPresentation`](../ipresentation) instancia, hasta que se elimine . [`IsTemporaryFilesAllowed`](../iblobmanagementoptions/istemporaryfilesallowed)se debe establecer en verdadero para usar este comportamiento, de lo contrario, se lanzará una excepción. Se recomienda este comportamiento, es más rápido y consume menos memoria queLoadAndRelease . |

### Ver también

* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
