---
title: PresentationLockingBehavior
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa o comportamento em relação ao tratamento do  arquivo de origem ou  java.io.InputStream ao carregar e trabalhar com uma instância de .
type: docs
url: /pt/com.aspose.slides/presentationlockingbehavior/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

Representa o comportamento em relação ao tratamento da fonte [IPresentation](../../com.aspose.slides/ipresentation) (arquivo ou java.io.InputStream) ao carregar e trabalhar com uma instância de [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```


--------------------

A fonte é o parâmetro passado ao construtor [IPresentation](../../com.aspose.slides/ipresentation). No exemplo abaixo, a fonte é o arquivo "pres.pptx": Para este exemplo, a fonte (arquivo "pres.pptx") ficará bloqueada por toda a vida útil da instância [IPresentation](../../com.aspose.slides/ipresentation), ou seja, não pode ser alterada ou excluída por outro processo.
## Campos

| Campo | Descrição |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | A fonte ficará bloqueada apenas durante a execução do construtor [IPresentation](../../com.aspose.slides/ipresentation). |
| [KeepLocked](#KeepLocked) | A fonte ficará bloqueada por toda a vida útil da instância [IPresentation](../../com.aspose.slides/ipresentation), até que seja descartada. |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```

A fonte ficará bloqueada apenas durante a execução do construtor [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

Se ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) estiver definido como false, todos os BLOBs serão carregados na memória. Caso contrário, outros meios, como arquivos temporários, podem ser usados.

--------------------

Esse comportamento é mais lento que [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) e, se for possível transferir a propriedade da fonte para [IPresentation](../../com.aspose.slides/ipresentation), recomenda-se usar [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked).

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

A fonte ficará bloqueada por toda a vida útil da instância [IPresentation](../../com.aspose.slides/ipresentation), até que seja descartada.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) deve ser definido como true para usar este comportamento, caso contrário será lançada uma exceção.

--------------------

Este comportamento é recomendado, pois é mais rápido e consome menos memória que [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease).