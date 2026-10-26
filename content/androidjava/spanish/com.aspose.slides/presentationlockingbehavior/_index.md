---
title: PresentationLockingBehavior
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa el comportamiento relativo al tratamiento del archivo fuente o java.io.InputStream al cargar y trabajar con una instancia de .
type: docs
url: /es/com.aspose.slides/presentationlockingbehavior/
---
**Herencia:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

Representa el comportamiento relativo al tratamiento de la [IPresentation](../../com.aspose.slides/ipresentation) fuente (archivo o java.io.InputStream) al cargar y trabajar con una instancia de [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

La fuente es el parámetro pasado al constructor [IPresentation](../../com.aspose.slides/ipresentation). En el ejemplo a continuación, la fuente es el archivo "pres.pptx": para este ejemplo, la fuente ("pres.pptx" file) permanecerá bloqueada durante la vida de una instancia [IPresentation](../../com.aspose.slides/ipresentation), es decir, no podrá ser cambiada o eliminada por otro proceso.
## Campos

| Campo | Descripción |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | La fuente permanecerá bloqueada sólo durante la ejecución del constructor [IPresentation](../../com.aspose.slides/ipresentation). |
| [KeepLocked](#KeepLocked) | La fuente permanecerá bloqueada durante toda la vida de una instancia [IPresentation](../../com.aspose.slides/ipresentation), hasta que sea eliminada. |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```

La fuente permanecerá bloqueada sólo durante la ejecución del constructor [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

Si ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) está configurado a false, todos los BLOB se cargarán en memoria. De lo contrario, se pueden usar otros medios, como archivos temporales.

--------------------

Este comportamiento es más lento que [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked), y si es posible pasar la propiedad de la fuente a [IPresentation](../../com.aspose.slides/ipresentation), se recomienda usar [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked).

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

La fuente permanecerá bloqueada durante toda la vida de una instancia [IPresentation](../../com.aspose.slides/ipresentation), hasta que sea eliminada.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) debe establecerse en true para usar este comportamiento, de lo contrario se lanzará una excepción.

--------------------

Este comportamiento se recomienda, es más rápido y consume menos memoria que [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease).