# Resume

## Ilnur Takchurin

---

## Contacts:

---

E-mail: _takchurinif@gmail.com_
Telegram: _+79964012438_

## About me:

---

I returned to programming after a few years of break and work in another field, I want to grow professionally. I develop myself every day

## Skills:

---

1 Graphic Editor: Figma. Photoshop
2 IDE: PhpStorm. VS Code
3 Version control system: Bitbucket
4 Gulp
5 HTML5 и CSS
6 Pug и SCSS
7 Bootstrap4
8 BEM

## Code examples:

---
```javascript
if (document.getElementById('slider')) {
    (function () {

        var slider = document.getElementById('slider');
        var rangePrice = [
            document.querySelector('#lower-price'),
            document.querySelector('#upper-price')
        ]

        noUiSlider.create(slider, {
            start: [0, 1000],
            connect: true,
            range: {
                'min': 0,
                'max': 12000
            }
        });

        slider.noUiSlider.on('update', function (values, handle) {
            if (handle === 0) {
                rangePrice[handle].value =  'от ' + Math.round(values[handle]) + ' ₽';
            } else {
                rangePrice[handle].value =  'до ' + Math.round(values[handle]) + ' ₽';
            }
        });

        rangePrice[0].addEventListener('change', function () {
            slider.noUiSlider.set([this.value.replace(/\D/g,''), null]);
        });

        rangePrice[1].addEventListener('change', function () {
            slider.noUiSlider.set([null, this.value.replace(/\D/g,'')]);
        });
    })();
}
```
## Experience:
---

7 months worked as a frontend developer in the company ГК Снег

## Education:
---

Graduated from the Financial University under the Government of the Russian Federation

## English:
---

According to the results of the tests, English proficiency at the A2 Pre-Intermediate
