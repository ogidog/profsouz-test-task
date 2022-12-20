# Комментарии к тестовому заданию

## Клиент Vue.js
```
Требуемая функциональность достигнута (на том или ином уровне). 
В текущей версии декомпозицию элементов не проводил. Все в одном файле MainContainer.vue. 
Если успею, то к среде (21.12.2022) сделаю декомпозицию и общий state через Vuex.

Могут быть какие-то баги. Код пока без комментариев.    
```

## Сервер express.js
```
Сделал на express.js.  Разбил логику (примитивную) на компоненты (routes/controllrs/services)
```

## Docker
```
Сделал два докера: клиент (nginx-proxy) и back-сервер (node.js)
Работают два контейнера: profsouz-test-task-frontend и profsouz-test-task-middleware
```

## Установка
```
1. Скачиваем или клонируем репозитарий
2. В локальной папке репозитария заходим в папку dockers
3. Запускаем docker compose up (Нужен установленный докер, например Windows Docker Desktop).

Если контейнеры запустились: сервис доступен по адресу http://localhost:8080
```
