---
title: IControl
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um controle ActiveX.
type: docs
url: /pt/com.aspose.slides/icontrol/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

Representa um controle ActiveX.
## Métodos

| Método | Descrição |
| --- | --- |
| [getName()](#getName--) | Retorna o nome deste controle. |
| [setName(String value)](#setName-java.lang.String-) | Retorna o nome deste controle. |
| [getClassId()](#getClassId--) | Obtém o ID de classe deste controle. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Retorna o objeto de propriedades de preenchimento de imagem ControlEx. |
| [getFrame()](#getFrame--) | Retorna ou define o quadro do controle. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Retorna ou define o quadro do controle. |
| [getProperties()](#getProperties--) | Retorna uma coleção de propriedades ActiveX. |
| [getPersistence()](#getPersistence--) | Obtém o método usado para armazenar as propriedades do controle ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Especifica a persistência de um controle ActiveX quando o método usado para persistir é PersistStream, PersistStreamInit ou PersistStorage. |
### getName() {#getName--}
```
public abstract String getName()
```

Retorna o nome deste controle. Leitura/gravação String.

**Retorna:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Retorna o nome deste controle. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

Obtém o ID de classe deste controle. Somente leitura java.util.UUID.

**Retorna:**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Retorna o objeto de propriedades de preenchimento de imagem ControlEx. Somente leitura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Retorna:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Retorna ou define o quadro do controle. Leitura/gravação [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Retorna:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Retorna ou define o quadro do controle. Leitura/gravação [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```

Retorna uma coleção de propriedades ActiveX. Somente leitura [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**Retorna:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```

Obtém o método usado para armazenar as propriedades do controle ActiveX. Somente leitura [PersistenceType](../../com.aspose.slides/persistencetype).

**Retorna:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

Especifica a persistência de um controle ActiveX quando o método usado para persistir é PersistStream, PersistStreamInit ou PersistStorage.

**Retorna:**
byte[]