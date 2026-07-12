---
title: EmbeddingLevel
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa os direitos de licenciamento para incorporação da fonte.
type: docs
url: /pt/com.aspose.slides/embeddinglevel/
---
**Herança:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

Representa os direitos de licenciamento para incorporação da fonte.
## Campos

| Campo | Descrição |
| --- | --- |
| [Installable](#Installable) | Fontes com esta configuração indicam que podem ser incorporadas e instaladas permanentemente no sistema remoto por um aplicativo. |
| [Restricted](#Restricted) | Fontes que têm apenas este bit definido não devem ser modificadas, incorporadas ou trocadas de qualquer forma sem antes obter permissão do proprietário legal. |
| [PreviewPrint](#PreviewPrint) | Quando este bit está definido, a fonte pode ser incorporada e carregada temporariamente no sistema remoto. |
| [Editable](#Editable) | Quando este bit está definido, a fonte pode ser incorporada, mas deve ser instalada temporariamente apenas em outros sistemas. |
| [NoSubsetting](#NoSubsetting) | Quando este bit está definido, a fonte não pode ser subconfigurada antes da incorporação. |
| [BitmapOnly](#BitmapOnly) | Quando este bit está definido, apenas bitmapas contidos na fonte podem ser incorporados. |
### Installable {#Installable}
```
public static final int Installable
```

Fontes com esta configuração indicam que podem ser incorporadas e instaladas permanentemente no sistema remoto por um aplicativo. O usuário do sistema remoto adquire os mesmos direitos, obrigações e licenças para essa fonte que o comprador original da fonte, e está sujeito ao mesmo contrato de licença de usuário final, direitos autorais, patente de design e/ou marca registrada que o comprador original.

### Restricted {#Restricted}
```
public static final int Restricted
```

Fontes que têm apenas este bit definido não devem ser modificadas, incorporadas ou trocadas de qualquer forma sem antes obter permissão do proprietário legal.

### PreviewPrint {#PreviewPrint}
```
public static final int PreviewPrint
```

Quando este bit está definido, a fonte pode ser incorporada e carregada temporariamente no sistema remoto. Documentos que contêm fontes Preview & Print devem ser abertos em "somente leitura"; nenhuma edição pode ser aplicada ao documento.

### Editable {#Editable}
```
public static final int Editable
```

Quando este bit está definido, a fonte pode ser incorporada, mas deve ser instalada temporariamente apenas em outros sistemas. Em contraste com as fontes Preview & Print, documentos que contêm fontes Editable podem ser abertos para leitura, a edição é permitida e as alterações podem ser salvas.

### NoSubsetting {#NoSubsetting}
```
public static final int NoSubsetting
```

Quando este bit está definido, a fonte não pode ser subconfigurada antes da incorporação. Outras restrições de incorporação especificadas nos bits 0-3 e 9 também se aplicam.

### BitmapOnly {#BitmapOnly}
```
public static final int BitmapOnly
```

Quando este bit está definido, apenas bitmapas contidos na fonte podem ser incorporados. Nenhum dado de contorno pode ser incorporado. Se não houver bitmapas disponíveis na fonte, então a fonte é considerada não incorporável e os serviços de incorporação falharão.