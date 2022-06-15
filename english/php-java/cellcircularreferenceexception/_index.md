---
title: CellCircularReferenceException
type: docs
weight: 0
url: /php-java/cellcircularreferenceexception/
---

# CellCircularReferenceException class

 The exception that is thrown when one or more circular references are detected where a formula refers to its
 own cell either directly or indirectly.
 

## Constructors

| name | description |
| --- | --- |
| [CellCircularReferenceException](/slides/php-java/cellcircularreferenceexception/cellcircularreferenceexception/)() | Initializes a new instance of the CellCircularReferenceException class. |
| [CellCircularReferenceException](/slides/php-java/cellcircularreferenceexception/cellcircularreferenceexception/)(String) | Initializes a new instance of the CellCircularReferenceException class with a specified error message. |
| [CellCircularReferenceException](/slides/php-java/cellcircularreferenceexception/cellcircularreferenceexception/)(String, RuntimeException) | Initializes a new instance of the CellCircularReferenceException class with a specified error message and a reference to the inner exception that is the cause of this exception. |
| [CellCircularReferenceException](/slides/php-java/cellcircularreferenceexception/cellcircularreferenceexception/)(String, String) | Initializes a new instance of the CellCircularReferenceException class with a specified error message and circular cell reference. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getReference](/slides/php-java/cellcircularreferenceexception/getreference/)() | String | Gets a circular cell reference. |
