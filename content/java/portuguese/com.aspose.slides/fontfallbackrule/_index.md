---
title: FontFallBackRule
second_title: Referência da API Aspose.Slides para Java
description: Representa a regra de fallback de fonte
type: docs
url: /pt/com.aspose.slides/fontfallbackrule/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

Representa a regra de fallback de fonte
## Construtores

| Construtor | Descrição |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | Cria nova instância. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | Cria nova instância. |
## Métodos

| Método | Descrição |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Adiciona nova(s) fonte(s) à lista de fontes FallBack. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Adiciona novas fontes à lista de fontes FallBack. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Obtém o primeiro índice do intervalo unicode contínuo. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | Obtém o primeiro índice do intervalo unicode contínuo. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Obtém o último índice do intervalo unicode contínuo. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | Obtém o último índice do intervalo unicode contínuo. |
| [getCount()](#getCount--) | Obtém o número de fontes realmente definidas para o intervalo. |
| [get_Item(int index)](#get-Item-int-) | Obtém o nome da fonte no índice especificado. |
| [clear()](#clear--) | Remove todas as fontes da lista. |
| [remove(String fontName)](#remove-java.lang.String-) | Remove a primeira ocorrência de uma fonte FallBack específica da lista. |
| [removeAt(int index)](#removeAt-int-) | Remove a fonte FallBack no índice especificado da lista. |
| [toArray()](#toArray--) | Cria e retorna um array com todas as fontes FallBack para esta regra. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Cria e retorna um array com todas as fontes FallBack do intervalo especificado na lista. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Retorna um índice da regra especificada na coleção. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```


Cria nova instância.

--------------------

> ```
> // Crie nova instância de FantFallBackRule com uma fonte.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Crie nova instância de FantFallBackRule com várias fontes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startIndex | long | Índice inicial do intervalo unicode |
| endIndex | long | Índice final do intervalo unicode |
| fontNames | java.lang.String | Nome ou nomes da fonte (separados por vírgula) para FallBack |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```


Cria nova instância.

--------------------

> ```
> // Crie nova instância de FantFallBackRule com duas fontes
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // Crie nova instância de FantFallBackRule com várias fontes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startIndex | long | Índice inicial do intervalo unicode |
| endIndex | long | Índice final do intervalo unicode |
| fontNames | java.lang.String[] | Nome ou nomes da fonte (separados por vírgula) para FallBack |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```


Adiciona nova(s) fonte(s) à lista de fontes FallBack.

--------------------

> ```
> // Crie nova instância de FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Adicione uma segunda fonte à regra 
>  newRule.addFallBackFonts("MS Gothic");
>  //Adicione a terceira e a quarta fontes à regra 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontName | java.lang.String | Nome ou nomes da fonte (separados por vírgula) para FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```


Adiciona novas fontes à lista de fontes FallBack.

--------------------

> ```
> //Create new instance of FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Add of another three fonts to the rule 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontNames | java.lang.String[] | Nome ou nomes da fonte (separados por vírgula) para FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```


Obtém o primeiro índice do intervalo unicode contínuo.

**Retorna:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```


Obtém o primeiro índice do intervalo unicode contínuo.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```


Obtém o último índice do intervalo unicode contínuo.

**Retorna:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```


Obtém o último índice do intervalo unicode contínuo.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```


Obtém o número de fontes realmente definidas para o intervalo. Somente leitura int.

**Retorna:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```


Obtém o nome da fonte no índice especificado. Somente leitura [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```


Remove todas as fontes da lista.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```


Remove a primeira ocorrência de uma fonte FallBack específica da lista.

--------------------

> ```
> // Crie uma regra que contém uma lista de fontes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Remova Tahoma da lista.
>  newRule.remove("Tahoma");
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontName | java.lang.String | O nome da fonte a ser removida da lista. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Remove a fonte FallBack no índice especificado da lista.

--------------------

> ```
> // Crie uma regra que contém uma lista de fontes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Removendo Tahoma da lista.
>  newRule.remove(2);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero da fonte a ser removida. |

### toArray() {#toArray--}
```
public final String[] toArray()
```


Cria e retorna um array com todas as fontes FallBack para esta regra.

--------------------

> ```
> // Crie uma regra que contém uma lista de fontes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Obtenha todos os nomes de fontes como array.
>  String[] fontNames = newRule.toArray();
```

**Retorna:**
java.lang.String[] - Array de String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```


Cria e retorna um array com todas as fontes FallBack do intervalo especificado na lista.

```
// Crie uma regra que contém uma lista de fontes.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Obtenha os dois últimos nomes de fontes como array.
 String[] fontNames = newRule.toArray(2, 2);
```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startIndex | int | Um índice da primeira fonte a ser adicionada. |
| count | int | Número de fontes a serem adicionadas. |

**Retorna:**
java.lang.String[] - Array de String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```


Retorna um índice da regra especificada na coleção.

--------------------

> ```
> // Crie uma regra que contém uma lista de fontes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Obtenha o índice de Tahoma.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontName | java.lang.String | Nome da fonte a ser encontrada. |

**Retorna:**
int - Índice da fonte ou -1 se a fonte não for encontrada na lista.