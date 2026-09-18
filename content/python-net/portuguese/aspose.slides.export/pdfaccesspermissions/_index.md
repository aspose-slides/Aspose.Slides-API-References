---
title: PdfAccessPermissions enumeration
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.export/pdfaccesspermissions/
---
## Enumeração PdfAccessPermissions

Contém um conjunto de bandeiras que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com 
            acesso de usuário.

O tipo PdfAccessPermissions expõe os seguintes membros:

## Campos

| Campo | Descrição |
| :- | :- |
| NONE | Especifica que um usuário não tem permissões de acesso. |
| PRINT_DOCUMENT | Especifica se um usuário pode imprimir o documento (possivelmente não no nível de qualidade mais alto, dependendo de <br/>            se o bit [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/pt/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT) também está definido). |
| MODIFY_CONTENT | Especifica se um usuário pode modificar o conteúdo do documento por operações diferentes daquelas controladas<br/>            pelos bits [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/pt/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS), [`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/pt/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS), [`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/pt/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT). |
| COPY_TEXT_AND_GRAPHICS | Especifica se um usuário pode copiar ou extrair de outra forma texto e gráficos do documento por operações <br/>            diferentes da controlada pelo bit [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/pt/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS). |
| ADD_OR_MODIFY_FIELDS | Especifica se um usuário pode adicionar ou modificar anotações de texto, preencher campos de formulário interativos e, se o bit<br/>            [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/pt/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) também estiver definido, criar ou modificar campos de formulário interativos (incluindo campos de assinatura <br/>            ). |
| FILL_EXISTING_FIELDS | Especifica se um usuário pode preencher campos de formulário interativos existentes (incluindo campos de assinatura), mesmo que<br/>            o bit [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/pt/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) esteja desmarcado. |
| EXTRACT_TEXT_AND_GRAPHICS | Especifica se um usuário pode extrair texto e gráficos para suporte de acessibilidade a usuários com deficiências<br/>            ou para outros fins. |
| ASSEMBLE_DOCUMENT | Especifica se um usuário pode montar o documento (inserir, girar ou excluir páginas e criar marcadores ou<br/>            imagens em miniatura), mesmo que o bit [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/pt/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) esteja desmarcado. |
| HIGH_QUALITY_PRINT | Especifica se um usuário pode imprimir o documento para uma representação a partir da qual uma cópia digital fiel do<br/>            conteúdo PDF poderia ser gerada. Quando este bit está desmarcado (e o bit [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/pt/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) está definido),<br/>            a impressão é limitada a uma representação de baixo nível da aparência, possivelmente com qualidade degradada. |

### Veja Também
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)