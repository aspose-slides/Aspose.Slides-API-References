---
title: ResourceLoadingAction
second_title: Referência da API Java do Aspose.Slides para Android
description: Especifica o modo de carregamento de recurso externo.
type: docs
url: /pt/com.aspose.slides/resourceloadingaction/
---
**Herança:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

Especifica o modo de carregamento de recurso externo.
## Campos

| Field | Descrição |
| --- | --- |
| [Default](#Default) | Aspose.Slides carregará o recurso externo normalmente. |
| [Skip](#Skip) | Aspose.Slides ignorará o carregamento do recurso externo. |
| [UserProvided](#UserProvided) | Aspose.Slides usará o array de bytes fornecido pelo usuário em [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) como dados da imagem. |
### Default {#Default}
```
public static final int Default
```


Aspose.Slides carregará o recurso externo normalmente.

### Skip {#Skip}
```
public static final int Skip
```


Aspose.Slides ignorará o carregamento do recurso externo. Apenas o link sem dados será armazenado para uma imagem.

### UserProvided {#UserProvided}
```
public static final int UserProvided
```


Aspose.Slides usará o array de bytes fornecido pelo usuário em [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) como dados da imagem.