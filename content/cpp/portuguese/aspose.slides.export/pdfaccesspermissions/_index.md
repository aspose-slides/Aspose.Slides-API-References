---
title: PdfAccessPermissions
second_title: Referência da API Aspose.Slides para C++
description: Contém um conjunto de bandeiras que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso do usuário.
type: docs
weight: 989
url: /pt/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enum

Contém um conjunto de bandeiras que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso do usuário.

```cpp
enum class PdfAccessPermissions
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| None | 0 | Especifica que um usuário não tem permissões de acesso. |
| PrintDocument | 4 | Especifica se um usuário pode imprimir o documento (possivelmente não no nível de qualidade mais alto, dependendo se o bit [PdfAccessPermissions::HighQualityPrint](./) também está definido). |
| ModifyContent | 8 | Especifica se um usuário pode modificar o conteúdo do documento por operações diferentes daquelas controladas pelos bits [PdfAccessPermissions::AddOrModifyFields](./), [PdfAccessPermissions::FillExistingFields](./), [PdfAccessPermissions::AssembleDocument](./). |
| CopyTextAndGraphics | 16 | Especifica se um usuário pode copiar ou de outra forma extrair texto e gráficos do documento por operações diferentes daquelas controladas pelo bit [PdfAccessPermissions::ExtractTextAndGraphics](./). |
| AddOrModifyFields | 32 | Especifica se um usuário pode adicionar ou modificar anotações de texto, preencher campos de formulário interativos e, se o bit [PdfAccessPermissions::ModifyContent](./) também estiver definido, criar ou modificar campos de formulário interativos (incluindo campos de assinatura). |
| FillExistingFields | 256 | Especifica se um usuário pode preencher campos de formulário interativos existentes (incluindo campos de assinatura), mesmo se o bit [PdfAccessPermissions::AddOrModifyFields](./) estiver desativado. |
| ExtractTextAndGraphics | 512 | Especifica se um usuário pode extrair texto e gráficos em apoio à acessibilidade para usuários com deficiência ou para outros fins. |
| AssembleDocument | 1024 | Especifica se um usuário pode montar o documento (inserir, girar ou excluir páginas e criar marcadores ou imagens em miniatura), mesmo se o bit [PdfAccessPermissions::ModifyContent](./) estiver desativado. |
| HighQualityPrint | 2048 | Especifica se um usuário pode imprimir o documento para uma representação a partir da qual uma cópia digital fiel do conteúdo PDF pode ser gerada. Quando este bit está desativado (e o bit [PdfAccessPermissions::PrintDocument](./) está definido), a impressão é limitada a uma representação de baixo nível da aparência, possivelmente de qualidade degradada. |

## Veja Também

* Namespace [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)