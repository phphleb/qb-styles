# qb
## Сборка CSS-стилей для адаптивности страницы

.qb-width-resp 
-----------------------------------
Адаптивная ширина элемента для мобильных устройств. При ширине экрана меньше 770px растягивает элемент по ширине родительского,  если больше, то по ширине вставленного контента, максимальное значение 1200px.

 
.qb-hide, .qb-none
-----------------------------------
Изначальная установка скрытия элемента, перебивается всеми другими стилями.



.qb-block, .qb-inline-block, .qb-inline 
-----------------------------------
Изначальная установка видимости элемента, соответственно block,inline-block или inline,  перебивается всеми другими стилями.

### При верстке для ПК с адаптацией под мобильный контент

.qb-down-lg-none, .qb-down-lg-block, .qb-down-lg-inline-block, .qb-down-lg-inline
-----------------------------------
При ширине экрана меньше 1200px. 
Ниспадающее свойство элемента для мониторов со средним размером экрана и ниже.

.qb-down-md-none, .qb-down-md-block, .qb-down-md-inline-block, .qb-down-md-inline
-----------------------------------
При ширине экрана меньше 992px. 
Ниспадающее свойство элемента для небольших размеров экранов, планшетов и ниже.

.qb-down-sm-none, .qb-down-sm-block, .qb-down-sm-inline-block, .qb-down-sm-inline
-----------------------------------
При ширине экрана меньше 769px. 
Ниспадающее свойство элемента для очень маленьких экранов, телефонов и ниже.

.qb-down-esm-none, .qb-down-esm-block, .qb-down-esm-inline-block, .qb-down-esm-inline
-----------------------------------
При ширине экрана меньше 480px. 
Ниспадающее свойство элемента для миниатюрных устройств и ниже.

.qb-down-nn-none, .qb-down-nn-block, .qb-down-nn-inline-block, .qb-down-nn-inline
-----------------------------------
При ширине экрана меньше 320px. 

### При верстке для мобильных устройств с адаптацией под ПК

.qb-up-lg-none, .qb-up-lg-block, .qb-up-lg-inline-block, .qb-up-lg-inline
-----------------------------------
При ширине экрана больше 1200px. 
Восходящее свойство элемента для широкоэкранных мониторов и выше.

.qb-up-md-none, .qb-up-md-block, .qb-up-md-inline-block, .qb-up-md-inline
-----------------------------------
При ширине экрана больше 992px. 
Восходящее свойство элемента для мониторов со средним размером экрана и выше.

.qb-up-sm-none, .qb-up-sm-block, .qb-up-sm-inline-block, .qb-up-sm-inline
-----------------------------------
При ширине экрана больше 769px. 
Восходящее свойство элемента для небольших размеров экранов, планшетов и выше.

.qb-up-esm-none, .qb-up-esm-block, .qb-up-esm-inline-block, .qb-up-esm-inline
-----------------------------------
При ширине экрана больше 480px. 
Восходящее свойство элемента для очень маленьких экранов, телефонов и выше.

.qb-up-nn-none, .qb-up-nn-block, .qb-up-nn-inline-block, .qb-up-nn-inline
-----------------------------------
При ширине экрана больше 320px. 
Восходящее свойство элемента для миниатюрных устройств и выше.

### Видимость элемента в промежуточных значениях ширины экрана

.qb-lg-none, .qb-lg-block, .qb-lg-inline-block, .qb-lg-inline
-----------------------------------
При ширине экрана больше 1200px. 
Свойство элемента для широкоэкранных мониторов.

.qb-md-none, .qb-md-block, .qb-md-inline-block, .qb-md-inline
-----------------------------------
При ширине экрана от 992px до 1200px. 
Свойство элемента для мониторов со средним размером экрана.

.qb-sm-none, .qb-sm-block, .qb-sm-inline-block, .qb-sm-inline
-----------------------------------
При ширине экрана от 769px до 992px. 
Свойство элемента для небольших размеров экранов, планшетов.

.qb-esm-none, .qb-esm-block, .qb-esm-inline-block, .qb-esm-inline
-----------------------------------
При ширине экрана от 480px до 769px. 
Свойство элемента для очень маленьких экранов, телефонов.

.qb-nn-none, .qb-nn-block, .qb-nn-inline-block, .qb-nn-inline
-----------------------------------
При ширине экрана меньше 480px. 
Свойство элемента для миниатюрных устройств.


.qb-print-none, .qb-print-block, .qb-print-inline, .qb-print-inline-block, .qb-print-table-column, .qb-print-table-cell, .qb-print-table
-----------------------------------
Отображение/скрытие элемента при печати.
