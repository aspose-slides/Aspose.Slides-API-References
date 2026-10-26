---
title: SlideShowTransition class
second_title: Referência de API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition classe

Representa a transição de apresentação de slides.

O tipo SlideShowTransition expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`sound`](/slides/python-net/pt/aspose.slides.slideshow/slideshowtransition/sound/) | Retorna ou define os dados de áudio incorporados.<br/>            Leitura/escrita [`IAudio`](/slides/python-net/pt/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/pt/aspose.slides.slideshow/slideshowtransition/sound_mode/) | Define ou retorna o modo de som para a transição de slide.<br/>            Leitura/escrita [`TransitionSoundMode`](/slides/python-net/pt/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/pt/aspose.slides.slideshow/slideshowtransition/sound_loop/) | Este atributo especifica se o som será repetido até que o próximo evento de som ocorra na<br/>            apresentação de slides.<br/>            Leitura/escrita **bool**. |
| [`advance_on_click`](/slides/python-net/pt/aspose.slides.slideshow/slideshowtransition/advance_on_click/) | Especifica se um clique do mouse avançará o slide ou não. Se este atributo não for<br/>            especificado, assume-se o valor verdadeiro.<br/>            Leitura/escrita **bool**. |
| [`advance_after`](/slides/python-net/pt/aspose.slides.slideshow/slideshowtransition/advance_after/) | Este atributo especifica se a apresentação de slides avançará para o próximo slide após um determinado tempo.<br/>            Leitura/escrita **bool**. |
| [`advance_after_time`](/slides/python-net/pt/aspose.slides.slideshow/slideshowtransition/advance_after_time/) | Especifica o tempo, em milissegundos, após o qual a transição deve iniciar. Esta configuração<br/>            pode ser usada em conjunto com o atributo advClick. Se este atributo não for especificado<br/>            assume-se que não ocorrerá avanço automático.<br/>            Leitura/escrita **int**. |
| [`speed`](/slides/python-net/pt/aspose.slides.slideshow/slideshowtransition/speed/) | Especifica a velocidade de transição a ser usada ao passar do slide atual<br/>            para o próximo.<br/>            Leitura/escrita [`TransitionSpeed`](/slides/python-net/pt/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/pt/aspose.slides.slideshow/slideshowtransition/value/) | Valor da transição da apresentação de slides.<br/>            Somente leitura [`ITransitionValueBase`](/slides/python-net/pt/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/pt/aspose.slides.slideshow/slideshowtransition/type/) | Tipo de transição.<br/>            Leitura/escrita [`TransitionType`](/slides/python-net/pt/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/pt/aspose.slides.slideshow/slideshowtransition/sound_is_built_in/) | Especifica se este som é um som embutido ou não. Se este atributo for definido como verdadeiro, então<br/>            a aplicação geradora é notificada para verificar o atributo name especificado para este som<br/>            em sua lista de sons embutidos e pode então apresentar um nome personalizado ou interface de usuário conforme necessário.<br/>            Leitura/escrita **bool**. |
| [`sound_name`](/slides/python-net/pt/aspose.slides.slideshow/slideshowtransition/sound_name/) | Especifica um nome legível por humanos para o som da transição. A propriedade [`SlideShowTransition.sound`](/slides/python-net/pt/aspose.slides.slideshow/slideshowtransition/sound) deve ser atribuída para obter ou definir o nome do som.<br/>            Leitura/escrita **str**. |
| [`duration`](/slides/python-net/pt/aspose.slides.slideshow/slideshowtransition/duration/) | Obtém ou define a duração do efeito de transição do slide em milissegundos.<br/>            Leitura/escrita **int**. |

### Veja também
* módulo [`aspose.slides.slideshow`](/slides/python-net/pt/aspose.slides.slideshow)
* biblioteca [`Aspose.Slides`](/slides/python-net)