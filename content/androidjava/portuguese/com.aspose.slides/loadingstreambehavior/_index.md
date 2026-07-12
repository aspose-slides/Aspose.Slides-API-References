---
title: LoadingStreamBehavior
second_title: Aspose.Slides para Android via Referência da API Java
description: O java.io.InputStream passado para um método é considerado um Binary Large Object (BLOB) veja a descrição.
type: docs
url: /pt/com.aspose.slides/loadingstreambehavior/
---
**Herança:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

O java.io.InputStream passado para um método é considerado um Binary Large Object (BLOB) (veja a descrição de [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)). Os valores desta enumeração identificam como o java.io.InputStream deve ser tratado quando é passado para o método. Dependendo dos requisitos, diferentes decisões podem ser tomadas para fornecer o comportamento mais eficiente.

## Campos

| Campo | Descrição |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | O stream será lido até o final e então liberado - ou seja |
| [KeepLocked](#KeepLocked) | O stream será travado dentro do objeto [IPresentation](../../com.aspose.slides/ipresentation), ou seja |

### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

O stream será lido até o final e então liberado - ou seja, será garantido que este stream não será usado pela instância [IPresentation](../../com.aspose.slides/ipresentation) no futuro. Ele pode ser fechado pelo código cliente ou usado de qualquer outra forma.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // o stream pode ser fechado, não é mais necessário para o objeto "pres".
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```


### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

O stream será travado dentro do objeto [IPresentation](../../com.aspose.slides/ipresentation), ou seja, a propriedade do stream será transferida. O objeto [IPresentation](../../com.aspose.slides/ipresentation) será responsável por descartar o stream corretamente quando este objeto for descartado. Esse comportamento é extremamente útil quando você precisa serializar um grande arquivo BLOB (como um vídeo ou áudio grande - veja a descrição de [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)) e deseja evitar carregar esse arquivo na memória ou outros problemas de desempenho. Você pode simplesmente abrir o java.io.FileInputStream para este arquivo e passá-lo para um método, escolhendo [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // Você não deve fechar o stream ou interagir com ele de qualquer outra forma, isso causará um erro no método Save.
>    // O fileStream será usado para salvar, o que evitará alto consumo de memória
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
