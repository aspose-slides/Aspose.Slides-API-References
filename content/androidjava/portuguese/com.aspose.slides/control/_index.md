---
title: Control
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um controle ActiveX.
type: docs
url: /pt/com.aspose.slides/control/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as interfaces implementadas:**
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)
```
public class Control extends DomObject<ControlCollection> implements IControl
```

Representa um controle ActiveX.
## Métodos

| Método | Descrição |
| --- | --- |
| [getPersistence()](#getPersistence--) | Obtém o método usado para armazenar as propriedades do controle ActiveX. |
| [getName()](#getName--) | Obtém ou define o nome deste controle. |
| [setName(String value)](#setName-java.lang.String-) | Obtém ou define o nome deste controle. |
| [getClassId()](#getClassId--) | Obtém o id da classe deste controle. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | Obtém o id da classe deste controle. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Retorna o objeto de propriedades de preenchimento de imagem do controle. |
| [getFrame()](#getFrame--) | Retorna ou define a moldura do controle. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Retorna ou define a moldura do controle. |
| [getProperties()](#getProperties--) | Retorna uma coleção de propriedades ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Especifica a persistência de um controle ActiveX quando o método usado para persistir é PersistStream, PersistStreamInit ou PersistStorage. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```

Obtém o método usado para armazenar as propriedades do controle ActiveX. Somente leitura [PersistenceType](../../com.aspose.slides/persistencetype).

--------------------

> ```
> Next example shows the using Persistence property for checking if properties of ActiveX object may be changed as XML based ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //Use seu próprio método para gerenciar propriedades ActiveX armazenadas em seu arquivo binário
>  }
> ```

**Retorna:**
int
### getName() {#getName--}
```
public final String getName()
```

Obtém ou define o nome deste controle. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Obtém ou define o nome deste controle. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

Obtém o id da classe deste controle. Somente leitura java.util.UUID.

**Retorna:**
java.util.UUID
### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

Obtém o id da classe deste controle. Somente leitura java.util.UUID.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Retorna o objeto de propriedades de preenchimento de imagem do controle. Somente leitura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Retorna:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Retorna ou define a moldura do controle. Leitura/Gravação [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Retorna:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Retorna ou define a moldura do controle. Leitura/Gravação [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

Retorna uma coleção de propriedades ActiveX. Somente leitura [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

Nota: Aspose.Slides suporta apenas propriedades ActiveX baseadas em XML. Se as propriedades forem armazenadas em formato binário, esta propriedade retornará null.

**Retorna:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

Especifica a persistência de um controle ActiveX quando o método usado para persistir é PersistStream, PersistStreamInit ou PersistStorage.

--------------------

> ```
> Next example shows the using ActiveXControlBinary property for changing ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //Use seu próprio método para gerenciar propriedades ActiveX armazenadas em seu arquivo binário
>  }
> ```

**Retorna:**
byte[]
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retorna o slide base. Somente leitura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Retorna:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retorna a apresentação. Somente leitura [IPresentation](../../com.aspose.slides/ipresentation).

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation)