# Getshoptv task

Проект выложен по адресу https://vlad-lis.github.io/getshoptv-task/

## Использованы:

- React + TypeScript
- SCSS
- Чуть-чуть redux :)
- React-input/mask для маски номера телефона
- Axios для запросов
- Eslint, prettier

## Реализованы требования:

- Три экрана (видео с баннером, промо и финальный экран)
- Навигация с помощью стрелок по кнопкам
- Ввод с клавиатуры
- Выбор кнопки на Enter
- Валидация формы (валидный номер и согласние на обработку ПД)
- Валидация номера через https://numverify.com/
- Пауза видео при переходе на экран с промо, возобновление при возвращении
- Таймер бездействия в 10 секунд для экрана с промо

## Запуск проекта

1. Клонировать репозиторий:

```
git clone git@github.com:vlad-lis/getshoptv-task.git
```

2. В папке с проектом установить зависимости:

```
npm i
```

3. Там же запустить проект:

```
npm run dev
```

Проект запустится локально адресу http://localhost:5173/getshoptv-task/
