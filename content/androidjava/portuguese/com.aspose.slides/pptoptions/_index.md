---
title: PptOptions
second_title: Aspose.Slides para Android via Referência da API Java
description: Fornece opções que controlam como uma apresentação é salva no formato PPT.
type: docs
url: /pt/com.aspose.slides/pptoptions/
---
**Herança:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IPptOptions](../../com.aspose.slides/ipptoptions), java.lang.Cloneable
```
public class PptOptions extends SaveOptions implements IPptOptions, Cloneable
```

Fornece opções que controlam como uma apresentação é salva no formato PPT.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PptOptions()](#PptOptions--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Representa o GUID da classe de objeto (CLSID) que está armazenado na entrada do diretório raiz. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Representa o GUID da classe de objeto (CLSID) que está armazenado na entrada do diretório raiz. |

### PptOptions() {#PptOptions--}
```
public PptOptions()
```

### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public final UUID getRootDirectoryClsid()
```

Representa o GUID da classe de objeto (CLSID) que está armazenado na entrada do diretório raiz. Pode ser usado para a ativação COM da aplicação do documento. O valor padrão é '64818D11-4F9B-11CF-86EA-00AA00B929E8' que corresponde a 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// definir CLSID para 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorno:**
java.util.UUID

### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public final void setRootDirectoryClsid(UUID value)
```

Representa o GUID da classe de objeto (CLSID) que está armazenado na entrada do diretório raiz. Pode ser usado para a ativação COM da aplicação do documento. O valor padrão é '64818D11-4F9B-11CF-86EA-00AA00B929E8' que corresponde a 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// definir CLSID para 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.util.UUID |  |