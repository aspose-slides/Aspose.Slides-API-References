---
title: FontsLoader
second_title: Aspose.Slides para Android via Referência da API Java
description: Classe para carregar fontes personalizadas definidas pelo usuário.
type: docs
url: /pt/com.aspose.slides/fontsloader/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

Classe para carregar fontes personalizadas definidas pelo usuário. Deve ser usada antes de criar quaisquer objetos de apresentação.

## Métodos

| Método | Descrição |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Adiciona pastas adicionais para buscar fontes. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Adiciona fonte a partir dos dados binários |
| [getFontFolders()](#getFontFolders--) | Obtém pastas de fontes. |
| [clearCache()](#clearCache--) | Libera todas as fontes personalizadas definidas pelo usuário |

### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```

Adiciona pastas adicionais para buscar fontes.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // pastas para buscar fontes
>  String[] folders = new String[] { dataDir };
>  // Carrega as fontes do diretório de fontes personalizadas
>  FontsLoader.loadExternalFonts(folders);
>  // Executa algum trabalho e realiza a renderização da apresentação/slides
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Limpar cache de fontes
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| directories | java.lang.String[] | Diretórios para ler fontes adicionais. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```

Adiciona fonte a partir dos dados binários

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | byte[] | Dados da fonte |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```

Obtém pastas de fontes. Retorna pastas que foram adicionadas com o método LoadExternalFonts, bem como pastas de fontes do sistema

**Retorna:**
java.lang.String[] - array contendo nomes de pastas

### clearCache() {#clearCache--}
```
public static void clearCache()
```

Libera todas as fontes personalizadas definidas pelo usuário

--------------------

Este método precisa limpar o cache com fontes personalizadas definidas pelo usuário.