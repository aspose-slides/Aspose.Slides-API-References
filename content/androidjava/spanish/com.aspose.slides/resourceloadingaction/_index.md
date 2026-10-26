---
title: ResourceLoadingAction
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Especifica el modo de carga de recursos externos.
type: docs
url: /es/com.aspose.slides/resourceloadingaction/
---
**Herencia:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

Especifica el modo de carga de recursos externos.
## Campos

| Campo | Descripción |
| --- | --- |
| [Default](#Default) | Aspose.Slides cargará el recurso externo como de costumbre. |
| [Skip](#Skip) | Aspose.Slides omitirá la carga del recurso externo. |
| [UserProvided](#UserProvided) | Aspose.Slides usará la matriz de bytes proporcionada por el usuario en [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) como datos de imagen. |
### Default {#Default}
```
public static final int Default
```


Aspose.Slides cargará el recurso externo como de costumbre.

### Skip {#Skip}
```
public static final int Skip
```


Aspose.Slides omitirá la carga del recurso externo. Sólo el enlace sin datos se almacenará para una imagen.

### UserProvided {#UserProvided}
```
public static final int UserProvided
```


Aspose.Slides usará la matriz de bytes proporcionada por el usuario en [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) como datos de imagen.