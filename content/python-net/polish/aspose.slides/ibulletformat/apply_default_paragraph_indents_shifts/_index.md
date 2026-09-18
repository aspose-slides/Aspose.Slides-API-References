---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides dla Pythona przez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Ustawia domyślne, niezerowe przesunięcia dla efektywnego wcięcia akapitu (Indent) i lewego marginesu (MarginLeft), gdy włączone są wypunktowania (tak jak PowerPoint robi, jeśli włączone są wypunktowania/ numerowanie w akapicie). Jeśli wypunktowanie jest wyłączone, po prostu resetuje wcięcie akapitu (Indent) i lewy margines (MarginLeft) (tak jak PowerPoint robi, jeśli wyłącza wypunktowanie/ numerowanie w akapicie). Przesunięcia wcięć są stosowane względem bieżącego kontekstu wypunktowania – IBulletFormat.Type, .NumberedBulletStyle oraz wysokości czcionki pierwszej części. Niezerowe przesunięcia wcięć są stosowane do efektywnego wcięcia (Indent) i lewego marginesu (MarginLeft) bieżącego akapitu (sprawiając, że wartości wynikowe są wartościami lokalnymi).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wywołanie tej metody nie ma znaczenia i powoduje wyrzucenie **System.InvalidOperationException** w następujących przypadkach:<br/>            jeśli obiekt nadrzędny sformatowany nie jest akapitem (na przykład wywołanie ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() spowoduje wyjątek);<br/>            lub jeśli akapit nie został dodany do żadnej kolekcji ITextFrame.Paragraphs (dodaj go najpierw); |



### Zobacz także
* klasa [`IBulletFormat`](/slides/python-net/pl/aspose.slides/ibulletformat)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)