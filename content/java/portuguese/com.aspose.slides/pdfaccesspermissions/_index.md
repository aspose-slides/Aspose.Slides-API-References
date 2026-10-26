---
title: PdfAccessPermissions
second_title: Referência da API Aspose.Slides para Java
description: Contém um conjunto de flags que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso de usuário.
type: docs
url: /pt/com.aspose.slides/pdfaccesspermissions/
---
**Herança:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

Contém um conjunto de flags que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso de usuário.
## Campos

| Campo | Descrição |
| --- | --- |
| [None](#None) | Especifica que um usuário não tem permissões de acesso. |
| [PrintDocument](#PrintDocument) | Especifica se um usuário pode imprimir o documento (possivelmente não no nível de qualidade mais alto, dependendo se a flag [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) também está definida). |
| [ModifyContent](#ModifyContent) | Especifica se um usuário pode modificar o conteúdo do documento por operações diferentes daquelas controladas pelas flags [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument). |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | Especifica se um usuário pode copiar ou extrair texto e gráficos do documento por operações diferentes daquelas controladas pela flag [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics). |
| [AddOrModifyFields](#AddOrModifyFields) | Especifica se um usuário pode adicionar ou modificar anotações de texto, preencher campos de formulário interativos e, se a flag [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) também estiver definida, criar ou modificar campos de formulário interativos (incluindo campos de assinatura). |
| [FillExistingFields](#FillExistingFields) | Especifica se um usuário pode preencher campos de formulário interativos existentes (incluindo campos de assinatura), mesmo se a flag [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) estiver desmarcada. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | Especifica se um usuário pode extrair texto e gráficos em apoio à acessibilidade para usuários com deficiência ou para outros fins. |
| [AssembleDocument](#AssembleDocument) | Especifica se um usuário pode montar o documento (inserir, girar ou excluir páginas e criar marcadores ou imagens em miniatura), mesmo se a flag [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) estiver desmarcada. |
| [HighQualityPrint](#HighQualityPrint) | Especifica se um usuário pode imprimir o documento para uma representação a partir da qual uma cópia digital fiel do conteúdo PDF poderia ser gerada. |
### None {#None}
```
public static final int None
```

Especifica que um usuário não tem permissões de acesso.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

Especifica se um usuário pode imprimir o documento (possivelmente não no nível de qualidade mais alto, dependendo se a flag [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) também está definida).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Especifica se um usuário pode modificar o conteúdo do documento por operações diferentes daquelas controladas pelas flags [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument).

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

Especifica se um usuário pode copiar ou extrair texto e gráficos do documento por operações diferentes daquelas controladas pela flag [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics).

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

Especifica se um usuário pode adicionar ou modificar anotações de texto, preencher campos de formulário interativos e, se a flag [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) também estiver definida, criar ou modificar campos de formulário interativos (incluindo campos de assinatura).

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

Especifica se um usuário pode preencher campos de formulário interativos existentes (incluindo campos de assinatura), mesmo se a flag [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) estiver desmarcada.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

Especifica se um usuário pode extrair texto e gráficos em apoio à acessibilidade para usuários com deficiência ou para outros fins.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

Especifica se um usuário pode montar o documento (inserir, girar ou excluir páginas e criar marcadores ou imagens em miniatura), mesmo se a flag [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) estiver desmarcada.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

Especifica se um usuário pode imprimir o documento para uma representação a partir da qual uma cópia digital fiel do conteúdo PDF poderia ser gerada. Quando esta flag está desmarcada (e a flag [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) está definida), a impressão é limitada a uma representação de nível baixo da aparência, possivelmente de qualidade degradada.