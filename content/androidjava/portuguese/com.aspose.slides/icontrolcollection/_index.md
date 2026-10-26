---
title: IControlCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Uma coleção de controles ActiveX.
type: docs
url: /pt/com.aspose.slides/icontrolcollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

Uma coleção de controles ActiveX.
## Métodos

| Método | Descrição |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Remove um controle ActiveX da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove um controle ActiveX armazenado na posição especificada da coleção. |
| [clear()](#clear--) | Remove todos os controles da coleção. |
| [get_Item(int index)](#get-Item-int-) | Retorna um controle na posição especificada. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Cria e adiciona um novo controle à coleção. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```


Remove um controle ActiveX da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Um controle a ser removido. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Remove um controle ActiveX armazenado na posição especificada da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de um controle a ser removido. |

### clear() {#clear--}
```
public abstract void clear()
```


Remove todos os controles da coleção.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```


Retorna um controle na posição especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de um controle. |

**Retorna:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```


Cria e adiciona um novo controle à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| controlType | int | Tipo de um controle a ser adicionado. |
| x | float | A coordenada X do lado esquerdo da moldura da forma. |
| y | float | A coordenada Y do lado superior da moldura da forma. |
| width | float | A largura da moldura da forma. |
| height | float | A altura da moldura da forma. |

**Retorna:**
[IControl](../../com.aspose.slides/icontrol) - Controle criado [IControl](../../com.aspose.slides/icontrol).