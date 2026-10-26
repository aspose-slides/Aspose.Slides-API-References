---
title: IFontFallBackRule
second_title: Aspose.Slides for Android via Java API Reference
description: Represents font fallback rule
type: docs
url: /pt/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

Representa regra de fallback de fonte
## Métodos

| Método | Descrição |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Adiciona nova(s) fonte(s) à lista de fontes FallBack. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Adiciona nova(s) fonte(s) à lista de fontes FallBack. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Obtém o primeiro índice de intervalo unicode contínuo. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Obtém o último índice de intervalo unicode contínuo. |
| [getCount()](#getCount--) | Obtém o número de fontes realmente definidas para o intervalo. |
| [get_Item(int index)](#get-Item-int-) | Obtém o nome da fonte no índice especificado. |
| [clear()](#clear--) | Remove todas as fontes da lista. |
| [remove(String fontName)](#remove-java.lang.String-) | Remove a primeira ocorrência de uma fonte FallBack específica da lista. |
| [removeAt(int index)](#removeAt-int-) | Remove a fonte FallBack no índice especificado da lista. |
| [toArray()](#toArray--) | Cria e retorna um array com todas as fontes FallBack para esta regra. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Cria e retorna um array com todas as fontes FallBack do intervalo especificado na lista. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Retorna o índice da regra especificada na coleção. |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

Adiciona nova(s) fonte(s) à lista de fontes FallBack.

--------------------

> ```
> //Criar nova instância de FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Adicionar uma segunda fonte à regra 
>  newRule.addFallBackFonts("MS Gothic");
>  //Adicionar terceira e quarta fontes à regra 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontName | java.lang.String | Nome ou nomes da fonte (separados por vírgula) para FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

Adiciona nova(s) fonte(s) à lista de fontes FallBack.

--------------------

> ```
> //Criar nova instância de FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Adicionar mais três fontes à regra 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontNames | java.lang.String[] | Nome ou nomes da fonte (separados por vírgula) para FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

Obtém o primeiro índice de intervalo unicode contínuo.

**Retorna:**
long

### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

Obtém o último índice de intervalo unicode contínuo.

**Retorna:**
long

### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtém o número de fontes realmente definidas para o intervalo.

**Retorna:**
int

### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

Obtém o nome da fonte no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
java.lang.String

### clear() {#clear--}
```
public abstract void clear()
```

Remove todas as fontes da lista.

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```

Remove a primeira ocorrência de uma fonte FallBack específica da lista.

--------------------

> ```
> // Criar uma regra que contém uma lista de fontes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Removendo Tahoma da lista
>  newRule.remove("Tahoma");
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontName | java.lang.String | O nome da fonte a ser removida da lista. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Remove a fonte FallBack no índice especificado da lista.

--------------------

> ```
> // Criar uma regra que contém uma lista de fontes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Removendo Tahoma da lista
>  newRule.remove(2);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero da fonte a ser removida. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

Cria e retorna um array com todas as fontes FallBack para esta regra.

--------------------

> ```
> // Criar uma regra que contém uma lista de fontes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Obter todos os nomes de fontes como array
>  String[] fontNames = newRule.toArray();
> ```

**Retorna:**
java.lang.String[] - Array de String

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

Cria e retorna um array com todas as fontes FallBack do intervalo especificado na lista.

--------------------

> ```
> // Criar uma regra que contém uma lista de fontes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Obter os dois últimos nomes de fontes como array
>  String[] fontNames = newRule.toArray(2,2);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startIndex | int | Um índice da primeira fonte a ser adicionada. |
| count | int | Um número de fontes a ser adicionada. |

**Retorna:**
java.lang.String[] - Array de String

### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

Retorna o índice da regra especificada na coleção.

--------------------

> ```
> // Criar uma regra que contém uma lista de fontes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Obter índice de Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontName | java.lang.String | Nome da fonte a ser encontrada. |

**Retorna:**
int - Índice da fonte ou -1 se a fonte não for encontrada na lista.