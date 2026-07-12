---
title: IControlPropertiesCollection
second_title: Referência da API Java do Aspose.Slides para Android
description: Uma coleção de controles ActiveX.
type: docs
url: /pt/com.aspose.slides/icontrolpropertiescollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

Uma coleção de controles ActiveX.
## Métodos

| Método | Descrição |
| --- | --- |
| [getCount()](#getCount--) | Retorna o número de propriedades na coleção. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Adiciona uma propriedade à coleção. |
| [remove(String name)](#remove-java.lang.String-) | Remove uma propriedade com o nome especificado. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Retorna ou define a propriedade. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Retorna ou define a propriedade. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Retorna o número de propriedades na coleção. |
| [clear()](#clear--) | Remove todas as propriedades. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Retorna o número de propriedades na coleção. Somente leitura int.

**Retorna:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```


Adiciona uma propriedade à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | O nome da propriedade. |
| value | java.lang.String | O valor da propriedade. |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


Remove uma propriedade com o nome especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | O nome da propriedade a ser removida. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```


Retorna ou define a propriedade.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade. |

**Retorna:**
java.lang.String - Property.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```


Retorna ou define a propriedade.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```


Retorna o número de propriedades na coleção. Somente leitura [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Retorna:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```


Remove todas as propriedades.