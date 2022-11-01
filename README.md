# 54М-1

## Российский клон компьютера ZX Spectrum

Данная реплика восстановлена по известным схемам, которые были найдены на форуме zx-pk.ru. К сожалению, в более-менее нормальном качестве
удалось найти только фотографии с верхней стороны печатной платы. Нижнюю сторону пришлось трассировать заново.

Есть несколько вариантов данной схемы. Эта более поздняя, с дополнительной микросхемой ТМ2, для возможности использования кварцевого резонатора на 14МГц.
Схема так же содержит параметрический стабилизатор на микросхеме КР142ЕН5 (LM7805). Диоды VD5-VD12 в оригинале расппаиваются на плате клавиатуры. Я их разместил
на обратной стороне основной платы в корпусах SMD, так же добавил разъем X8 для подключения клавиатуры. При желании, можно не запаивать не то и не другое и подключаться 
напрямую к контактам системного разъема. Системный разъем так же заменен с оригинального ГРПМ1-61 на современный  64-пиновый.

Информация по данному клону на форумах:

[zx-pk.ru](https://zx-pk.ru/threads/33139-leningrad-0-aka-voenmekh-54m-1.html)

[ruecm.forum2x2.ru](https://ruecm.forum2x2.ru/t1172-topic)


## Особенности:
- Z80 CPU на чатоте 3,5МГц
- Одно поле памяти 48k на микросхемах DRAM КР565РУ5.

![image](Export/render.jpg)

[Принципиальная схема](Export/Schematics-54M-1_v1.0.0.pdf)

[Монтажная схема](Export/PCB_54M-1_v1.0.0.pdf)

[Чат Scorpion ZS & Ленинград в Telegram](https://t.me/zs_scorpion)

## Внимание!
- По данной схеме и герберам плата изготавливалась но пока не отлаживалась.

