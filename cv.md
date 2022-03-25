# rsschool-cv

## Olga Kuryanovich

### Contacts:
+ **Address:** Minsk, Belarus
+ **Phone:** +37529-7745541
+ **E-mail:** olechkamg@mail.ru
+ **GitHub:** liafokus
+ **Discord:** #9539


### About myself:
I am 29 years old. For the last 9 years I have been working as an administrator in restaurants and nightclubs. A year ago, I decided to radically change the scope of work and began to study in IT.
I stand out with perseverance and discipline. I know how to allocate time and find the necessary information. I hope to find a job this year in which I can express myself as much as possible.


### Skills:
+ HTML
+ CSS
+ JavaScript (Fundamentals, DOM)
+ Figma
+ Version control: Git (remote service GitHub)


### Code examples:
``` 
const tabs = document.querySelectorAll('.tabheader__item'),
           tabsContent = document.querySelectorAll('.tabcontent'),
           tabsParent = document.querySelector('.tabheader__items');

     function hideTabContent() {
         tabsContent.forEach(item => {
             item.classList.add('hide');
             item.classList.remove('show', 'fade');
         });

         tabs.forEach(item => {
             item.classList.remove('tabheader__item_active');
         });
     }

     function showTabContent(i = 0) {
         tabsContent[i].classList.add('show', 'fade');
         tabsContent[i].classList.remove('hide');
         tabs[i].classList.add('tabheader__item_active');
     }

    hideTabContent();
    showTabContent();
```

### Experience:
+ [educational project] (https://github.com/liafokus/liafokus.github.io.git)


### Education and courses:
+ **2020-2021** - IT-college Digital Unicorn (UX/UI design)
+ **2021** - Udemy (Web-design in Figma)
+ **2021** - IT-Academy (HTML,CSS & JS)
+ **2021-...** - Udemy (The Complete JavaScript + React Course - From Zero to Result)


### Languages:
+ **English** - A2-B1



