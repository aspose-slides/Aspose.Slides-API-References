---
title: setDifferential
type: docs
weight: 110
url: /php-java/mathbox/setdifferential/
---

# setDifferential(boolean) method

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

