---
title: OleObjectFrame
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um objeto OLE em um slide.
type: docs
url: /pt/com.aspose.slides/oleobjectframe/
---
**Herança:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

Representa um objeto OLE em um slide.

--------------------

> ```
> O exemplo a seguir mostra como acessar quadros de objeto OLE.
>  
  
>  // Carrega o PPTX para um objeto de apresentação
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // Acessa o primeiro slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Converte a forma para OleObjectFrame
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // Lê o objeto OLE e grava no disco
>      if (oleObjectFrame != null) {
>          // Obtém os dados do arquivo incorporado
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // Obtém a extensão do arquivo incorporado
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // Cria um caminho para salvar o arquivo extraído
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // Salva os dados extraídos
>          FileOutputStream fos = null;
>          try {
>              fos = new FileOutputStream(extractedPath);
>              fos.write(data);
>          } finally {
>              if (fos != null) fos.close();
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Métodos

| Método | Descrição |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Retorna OleObject image fill properties object. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Retorna ou define o título para o ícone OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Retorna ou define o título para o ícone OleObject. |
| [getObjectName()](#getObjectName--) | Retorna ou define o nome de um objeto. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Retorna ou define o nome de um objeto. |
| [getObjectProgId()](#getObjectProgId--) | Retorna o ProgID de um objeto. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Retorna o ProgID de um objeto. |
| [getLinkFileName()](#getLinkFileName--) | Retorna o caminho completo para um arquivo vinculado. |
| [getLinkPathLong()](#getLinkPathLong--) | Retorna o caminho completo para um arquivo vinculado. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Retorna o caminho completo para um arquivo vinculado. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Retorna o caminho relativo para um arquivo vinculado, se presente; caso contrário, retorna uma string vazia. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Retorna o nome do arquivo do objeto OLE incorporado |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Retorna o caminho do objeto OLE incorporado |
| [getEmbeddedData()](#getEmbeddedData--) | Obtém ou define informações sobre dados OLE incorporados. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Define informações sobre dados OLE incorporados. |
| [isObjectIcon()](#isObjectIcon--) | Determina se um objeto é visível como ícone. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Determina se um objeto é visível como ícone. |
| [isObjectLink()](#isObjectLink--) | Determina se um objeto está vinculado a um arquivo externo. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Determina se o objeto incorporado vinculado é atualizado automaticamente quando a apresentação é aberta ou impressa. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Determina se o objeto incorporado vinculado é atualizado automaticamente quando a apresentação é aberta ou impressa. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Retorna OleObject image fill properties object. Somente leitura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Retorna:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

Retorna ou define o título para o ícone OleObject. Leitura/gravação String.

--------------------

Quando IsObjectIcon == false este valor é ignorado. A string pode ser truncada de acordo com o tamanho do ícone Ole.

**Retorna:**
java.lang.String

### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

Retorna ou define o título para o ícone OleObject. Leitura/gravação String.

--------------------

Quando IsObjectIcon == false este valor é ignorado. A string pode ser truncada de acordo com o tamanho do ícone Ole.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

Retorna ou define o nome de um objeto. Leitura/gravação String.

**Retorna:**
java.lang.String

### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

Retorna ou define o nome de um objeto. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

Retorna o ProgID de um objeto. Somente leitura String.

**Retorna:**
java.lang.String

### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

Retorna o ProgID de um objeto. Somente leitura String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

Retorna o caminho completo para um arquivo vinculado. O nome de arquivo curto será usado. Somente leitura String.

**Retorna:**
java.lang.String

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Retorna o caminho completo para um arquivo vinculado. O nome de arquivo longo será usado. Leitura/gravação String.

**Retorna:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Retorna o caminho completo para um arquivo vinculado. O nome de arquivo longo será usado. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
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

Nas apresentações Ppt, alguns links de objetos Ole podem ter uma representação relativa.

**Retorna:**
java.lang.String

### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```

Retorna o nome do arquivo do objeto OLE incorporado

**Retorna:**
java.lang.String

### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

Retorna o caminho do objeto OLE incorporado

**Retorna:**
java.lang.String

### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

Obtém ou define informações sobre dados OLE incorporados. Leitura/gravação [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Retorna:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Define informações sobre dados OLE incorporados.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
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
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Dados incorporados [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) |

Este método altera as propriedades do objeto para refletir os novos dados e define o sinalizador IsObjectLink como false, indicando que o objeto OLE está incorporado. |

### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

Determina se um objeto é visível como ícone. Leitura/gravação  boolean .

**Retorna:**
boolean

### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

Determina se um objeto é visível como ícone. Leitura/gravação  boolean .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

Determina se um objeto está vinculado a um arquivo externo. Somente leitura  boolean .

**Retorna:**
boolean

### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

Determina se o objeto incorporado vinculado é atualizado automaticamente quando a apresentação é aberta ou impressa. Leitura/gravação  boolean .

**Retorna:**
boolean

### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

Determina se o objeto incorporado vinculado é atualizado automaticamente quando a apresentação é aberta ou impressa. Leitura/gravação  boolean .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |