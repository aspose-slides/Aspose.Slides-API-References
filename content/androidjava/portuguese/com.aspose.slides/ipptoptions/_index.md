---
title: IPptOptions
second_title: Aspose.Slides para Android via Referência da API Java
description: Fornece opções que controlam como uma apresentação é salva no formato PPT.
type: docs
url: /pt/com.aspose.slides/ipptoptions/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

Fornece opções que controlam como uma apresentação é salva no formato PPT.
## Métodos

| Método | Descrição |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Representa o GUID da classe de objeto (CLSID) que é armazenado na entrada do diretório raiz. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Representa o GUID da classe de objeto (CLSID) que é armazenado na entrada do diretório raiz. |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```

Representa o GUID da classe de objeto (CLSID) que é armazenado na entrada do diretório raiz. Pode ser usado para ativação COM da aplicação do documento. O valor padrão é '64818D11-4F9B-11CF-86EA-00AA00B929E8' que corresponde a 'Microsoft Powerpoint.Slide.8'.

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

**Retorna:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public abstract void setRootDirectoryClsid(UUID value)
```

Representa o GUID da classe de objeto (CLSID) que é armazenado na entrada do diretório raiz. Pode ser usado para ativação COM da aplicação do documento. O valor padrão é '64818D11-4F9B-11CF-86EA-00AA00B929E8' que corresponde a 'Microsoft Powerpoint.Slide.8'.

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