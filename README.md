# Vue Calendar of Events
Events(Content) for Vue.js datepicker.

Used: [vue.js](https://github.com/vuejs/vue), [moment.js](https://github.com/moment/moment), [vuejs-datepicker.js](https://github.com/charliekassel/vuejs-datepicker)

## Create your categories: ##
```
cats: [ // menu generate
{ text: 'All', icon: '&#9733;' }, // don't touch
{ text: 'Theme 1', icon: '&#9734;' }, // <-- remove or edit
...
{ text: 'Theme 5', icon: '&#9734;' } // <-- enter your new category
],
```

## Create your items: ##
```
items: [ // объект для генерации контента
{ day: 20, month: 1, year: 2019, cat: 1, title: 'Test Event #1', desc: 'Test description for test event.', icon: '&#10026;', vip: 0 },
{ day: 30, month: 1, year: 2019, cat: 1, title: 'New test Event #1', desc: 'New description for test event.', icon: '&#10026;', vip: 0 },
...
],
```
