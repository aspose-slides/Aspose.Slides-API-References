---
title: LoadingStreamBehavior
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: El java.io.InputStream pasado a un método se considera como un Binary Large Object (BLOB) ver description.
type: docs
url: /es/com.aspose.slides/loadingstreambehavior/
---
**Herencia:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

El java.io.InputStream pasado a un método se considera como un Binary Large Object (BLOB) (ver [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) description). Los valores de esta enumeración identifican cómo debe tratarse el java.io.InputStream cuando se pasa al método. Dependiendo de los requisitos, se pueden tomar diferentes decisiones para proporcionar el comportamiento más eficiente.

## Campos

| Campo | Descripción |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | El flujo se leerá hasta el final y luego se liberará - i.e. |
| [KeepLocked](#KeepLocked) | El flujo se bloqueará dentro del objeto [IPresentation](../../com.aspose.slides/ipresentation), i.e. |

### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

El flujo se leerá hasta el final y luego se liberará, es decir, se garantizará que este flujo no será utilizado por la instancia [IPresentation](../../com.aspose.slides/ipresentation) en el futuro. Puede ser cerrado por el código cliente o utilizado de cualquier otra manera.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // el flujo puede cerrarse, ya no es necesario para el objeto "pres".
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

El flujo se bloqueará dentro del objeto [IPresentation](../../com.aspose.slides/ipresentation), i.e. la propiedad del flujo será transferida. El objeto [IPresentation](../../com.aspose.slides/ipresentation) será responsable de disponer correctamente del flujo cuando este objeto se libere a su vez. Este comportamiento es extremadamente útil cuando necesita serializar un archivo BLOB grande (como un video o audio de gran tamaño -see [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) description) y desea evitar cargar este archivo en memoria o enfrentar otros problemas de rendimiento. Puede simplemente abrir el java.io.FileInputStream para este archivo y pasarlo a un método, eligiendo [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // No debe cerrar el flujo ni interactuar con él de ninguna otra manera, ya que provocará un error en el método Save.
>    // El fileStream se usará para guardar, lo que evitará un alto consumo de memoria
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
