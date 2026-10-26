---
title: Fonts
second_title: Referência da API Java Aspose.Slides para Android
description: Coleção de fontes.
type: docs
url: /pt/com.aspose.slides/fonts/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

Coleção de fontes.
## Métodos

| Método | Descrição |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | Retorna um dicionário de todas as definições de fontes de script na apresentação. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Obtém o nome da fonte associado a uma tag de script específica do tema da apresentação. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Atribui um nome de fonte a uma tag de script específica, que define como o texto desse script será renderizado na apresentação. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Remove a configuração de fonte associada a uma tag de script específica da coleção de fontes do tema. |
| [getLatinFont()](#getLatinFont--) | Retorna ou define a fonte Latin. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Retorna ou define a fonte Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Retorna ou define a fonte East Asian. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Retorna ou define a fonte East Asian. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Retorna ou define a fonte complex script. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Retorna ou define a fonte complex script. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```


Retorna um dicionário de todas as definições de fontes de script na apresentação.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```


**Retorna:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Um dicionário que mapeia códigos de script para nomes de fontes.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```


Obtém o nome da fonte associado a uma tag de script específica do tema da apresentação.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| script | java.lang.String | O código de script BCP-47 (por exemplo, "Latn", "Cyrl", "Jpan") usado para identificar um sistema de escrita. |

**Retorna:**
java.lang.String - O nome da fonte usado para o script especificado, ou  null  se o script não estiver definido.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```


Atribui um nome de fonte a uma tag de script específica, que define como o texto desse script será renderizado na apresentação.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| script | java.lang.String | O código de script BCP-47 (por exemplo, "Arab", "Hebr", "Hans") identificando o sistema de escrita. |
| fontName | java.lang.String | O nome da fonte a ser atribuído ao script especificado. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```


Remove a configuração de fonte associada a uma tag de script específica da coleção de fontes do tema.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| script | java.lang.String | O código de script BCP-47 cuja configuração de fonte deve ser removida. |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```


Retorna ou define a fonte Latin. Leitura/gravação [IFontData](../../com.aspose.slides/ifontdata).

**Retorna:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```


Retorna ou define a fonte Latin. Leitura/gravação [IFontData](../../com.aspose.slides/ifontdata).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```


Retorna ou define a fonte East Asian. Leitura/gravação [IFontData](../../com.aspose.slides/ifontdata).

**Retorna:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```


Retorna ou define a fonte East Asian. Leitura/gravação [IFontData](../../com.aspose.slides/ifontdata).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```


Retorna ou define a fonte complex script. Leitura/gravação [IFontData](../../com.aspose.slides/ifontdata).

**Retorna:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```


Retorna ou define a fonte complex script. Leitura/gravação [IFontData](../../com.aspose.slides/ifontdata).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |