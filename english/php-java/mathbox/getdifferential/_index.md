---
title: getDifferential
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 60
url: /php-java/mathbox/getdifferential/
---

## getDifferential()  method

 Differential
 When true, the box acts as a differential (e.g., ?? in an integrand), and receives the appropriate 
 horizontal spacing for the mathematical differential.
 Default: false
 
Example:
 
```php
  $differential = new MathematicalText("dx")->toBox();
  $differential->setDifferential(true);
  $baseArg = new MathematicalText("x")->join($differential);
  $integral = $baseArg->integral(MathIntegralTypes.Simple, "0", "1");
```

### Returns
boolean


---


