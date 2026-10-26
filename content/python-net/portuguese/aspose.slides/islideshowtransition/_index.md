---
title: ISlideShowTransition class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/islideshowtransition/
---
## ISlideShowTransition classe

Representa a transição de apresentação de slides.

O tipo ISlideShowTransition expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`sound`](/slides/python-net/pt/aspose.slides/islideshowtransition/sound/) | Retorna ou define os dados de áudio incorporados.<br/>            Leitura-gravação [`IAudio`](/slides/python-net/pt/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/pt/aspose.slides/islideshowtransition/sound_mode/) | Define ou retorna o modo de som para a transição de slide.<br/>            Leitura-gravação [`TransitionSoundMode`](/slides/python-net/pt/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/pt/aspose.slides/islideshowtransition/sound_loop/) | Este atributo especifica se o som será repetido até que o próximo evento sonoro ocorra na<br/>            apresentação de slides.<br/>            Leitura-gravação **bool**. |
| [`advance_on_click`](/slides/python-net/pt/aspose.slides/islideshowtransition/advance_on_click/) | Especifica se um clique do mouse avançará o slide ou não. Se este atributo não for<br/>            especificado, assume-se o valor true.<br/>            Leitura-gravação **bool**. |
| [`advance_after`](/slides/python-net/pt/aspose.slides/islideshowtransition/advance_after/) | Este atributo especifica se a apresentação de slides avançará para o próximo slide após um determinado tempo.<br/>            Leitura/gravação **bool**. |
| [`advance_after_time`](/slides/python-net/pt/aspose.slides/islideshowtransition/advance_after_time/) | Especifica o tempo, em milissegundos, após o qual a transição deve iniciar. Esta configuração<br/>            pode ser usada em conjunto com o atributo advClick. Se este atributo não for especificado<br/>            assume-se que nenhum avanço automático ocorrerá.<br/>            Leitura-gravação **int**. |
| [`speed`](/slides/python-net/pt/aspose.slides/islideshowtransition/speed/) | Especifica a velocidade de transição a ser usada ao passar do slide atual<br/>            para o próximo.<br/>            Leitura-gravação [`TransitionSpeed`](/slides/python-net/pt/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/pt/aspose.slides/islideshowtransition/value/) | Valor da transição da apresentação de slides.<br/>            Somente-leitura [`ITransitionValueBase`](/slides/python-net/pt/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/pt/aspose.slides/islideshowtransition/type/) | Tipo de transição.<br/>            Leitura-gravação [`TransitionType`](/slides/python-net/pt/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/pt/aspose.slides/islideshowtransition/sound_is_built_in/) | Especifica se este som é um som interno ou não. Se este atributo for definido como true então<br/>            a aplicação geradora é notificada para verificar o atributo name especificado para este som<br/>            em sua lista de sons internos e pode então apresentar um nome personalizado ou UI conforme necessário.<br/>            Leitura-gravação **bool**. |
| [`sound_name`](/slides/python-net/pt/aspose.slides/islideshowtransition/sound_name/) | Especifica um nome legível por humanos para o som da transição. A propriedade [`ISlideShowTransition.sound`](/slides/python-net/pt/aspose.slides/islideshowtransition/sound) deve ser atribuída para obter ou definir o nome do som.<br/>            Leitura-gravação **str**. |
| [`duration`](/slides/python-net/pt/aspose.slides/islideshowtransition/duration/) | Obtém ou define a duração do efeito de transição do slide em milissegundos.<br/>            Leitura/gravação **int**. |

### Ver também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)