---
title: IOleObjectFrame
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um objeto OLE em um slide.
type: docs
url: /pt/com.aspose.slides/ioleobjectframe/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

Representa um objeto OLE em um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Retorna o objeto de propriedades de preenchimento de imagem OleObject. |
| [getObjectName()](#getObjectName--) | Retorna ou define o nome de um objeto. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Retorna ou define o nome de um objeto. |
| [getEmbeddedData()](#getEmbeddedData--) | Obtém informações sobre os dados incorporados OLE. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Define informações sobre os dados incorporados OLE. |
| [getObjectProgId()](#getObjectProgId--) | Retorna o ProgID de um objeto. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Retorna o ProgID de um objeto. |
| [getLinkFileName()](#getLinkFileName--) | Retorna o caminho completo para um arquivo vinculado. |
| [getLinkPathLong()](#getLinkPathLong--) | Retorna o caminho completo para um arquivo vinculado. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Retorna o caminho completo para um arquivo vinculado. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Retorna o caminho relativo para um arquivo vinculado, se presente; caso contrário, retorna uma string vazia. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Retorna o nome de arquivo do objeto OLE incorporado |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Retorna o caminho do objeto OLE incorporado |
| [isObjectIcon()](#isObjectIcon--) | Determina se um objeto é visível como ícone. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Determina se um objeto é visível como ícone. |
| [isObjectLink()](#isObjectLink--) | Determina se um objeto está vinculado a um arquivo externo. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Determina se o objeto incorporado vinculado é atualizado automaticamente quando a apresentação é aberta ou impressa. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Determina se o objeto incorporado vinculado é atualizado automaticamente quando a apresentação é aberta ou impressa. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Retorna ou define o título do ícone OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Retorna ou define o título do ícone OleObject. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```


Retorna o objeto de propriedades de preenchimento de imagem OleObject. Somente leitura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Retorna:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```


Retorna ou define o nome de um objeto. Leitura/gravação String.

**Retorna:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```


Retorna ou define o nome de um objeto. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```


Obtém informações sobre os dados incorporados OLE. Somente leitura [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Retorna:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```


Define informações sobre os dados incorporados OLE.

--------------------

> ```
> Following example demonstrates how to change OLE embedded data
>  and its type for existing [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) object 
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          BufferedInputStream bis = null;
>          DataInputStream dis = null;
>          try {
>              File file = new File("Picture.png");
>              byte[] bytes = new byte[(int) file.length()];
>              bis = new BufferedInputStream(new FileInputStream(file));
>              dis = new DataInputStream(bis);
>              dis.readFully(bytes);
>              IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(bytes, "png");
>              oof.setEmbeddedData(newData);
>          } finally {
>              if (dis != null) {
>                  dis.close();
>              if (bis != null)
>                  bis.close();
>              }
>          }
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Dados incorporados [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

--------------------

Este método altera as propriedades do objeto para refletir os novos dados e define o sinalizador IsObjectLink como false, indicando que o objeto OLE está incorporado. |

### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```


Retorna o ProgID de um objeto. Somente leitura String.

**Retorna:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```


Retorna o ProgID de um objeto. Somente leitura String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```


Retorna o caminho completo para um arquivo vinculado. O nome de arquivo abreviado será usado. Somente leitura String.

**Retorna:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Retorna o caminho completo para um arquivo vinculado. O nome de arquivo longo será usado. Leitura/gravação String.

**Retorna:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


Retorna o caminho completo para um arquivo vinculado. O nome de arquivo longo será usado. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```


Retorna o caminho relativo para um arquivo vinculado, se presente; caso contrário, retorna uma string vazia. Somente leitura String.

--------------------

> ```
> Presentation presentation = new Presentation("demo.ppt");
>  try {
>      IOleObjectFrame oleFrame = (IOleObjectFrame)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oleFrame != null)
>      {
>          System.out.println("The relative path: " + oleFrame.getLinkPathRelative());
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


--------------------

Nas apresentações Ppt, alguns links de objetos Ole podem ter representação relativa.

**Retorna:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```


Retorna o nome de arquivo do objeto OLE incorporado

**Retorna:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```


Retorna o caminho do objeto OLE incorporado

**Retorna:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```


Determina se um objeto é visível como ícone. Leitura/gravação boolean.

**Retorna:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```


Determina se um objeto é visível como ícone. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```


Determina se um objeto está vinculado a um arquivo externo. Somente leitura boolean.

**Retorna:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```


Determina se o objeto incorporado vinculado é atualizado automaticamente quando a apresentação é aberta ou impressa. Leitura/gravação boolean.

**Retorna:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```


Determina se o objeto incorporado vinculado é atualizado automaticamente quando a apresentação é aberta ou impressa. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```


Retorna ou define o título do ícone OleObject. Leitura/gravação String.

--------------------

Quando IsObjectIcon == false, esse valor é ignorado. A cadeia pode ser truncada de acordo com o tamanho do ícone OLE.

**Retorna:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```


Retorna ou define o título do ícone OleObject. Leitura/gravação String.

--------------------

Quando IsObjectIcon == false, esse valor é ignorado. A cadeia pode ser truncada de acordo com o tamanho do ícone OLE.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |