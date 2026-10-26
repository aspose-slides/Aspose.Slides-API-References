---
title: ControlPropertiesCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Uma coleção de propriedades AcitveX.
type: docs
url: /pt/com.aspose.slides/controlpropertiescollection/
---
**Herança:**  
java.lang.Object

**Todas as interfaces implementadas:**  
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)  
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

Uma coleção de propriedades AcitveX.

## Métodos

| Método | Descrição |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Adiciona uma propriedade à coleção. |
| [remove(String name)](#remove-java.lang.String-) | Remove uma propriedade com o nome especificado. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Retorna ou define a propriedade. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Retorna ou define a propriedade. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Retorna a coleção de nomes de propriedades. |
| [clear()](#clear--) | Remove todas as propriedades. |
| [getCount()](#getCount--) | Retorna o número de propriedades na coleção. |
| [iterator()](#iterator--) | Retorna um enumerador que itera pela coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para toda a coleção. |

### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

Adiciona uma propriedade à coleção.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | O nome da propriedade. |
| value | java.lang.String | O valor da propriedade. |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Remove uma propriedade com o nome especificado.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | O nome da propriedade a ser removida. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Retorna ou define a propriedade.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade. |

**Retorna:**  
java.lang.String - Propriedade.

### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Retorna ou define a propriedade.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

Retorna a coleção de nomes de propriedades. Somente leitura [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Retorna:**  
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)

### clear() {#clear--}
```
public final void clear()
```

Remove todas as propriedades.

### getCount() {#getCount--}
```
public final int getCount()
```

Retorna o número de propriedades na coleção. Somente leitura int.

**Retorna:**  
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Retorna um enumerador que itera pela coleção.

**Retorna:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Um IGenericEnumerator que pode ser usado para iterar pela coleção.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Retorna um iterador java para toda a coleção.

**Retorna:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Um java.util.Iterator para toda a coleção.