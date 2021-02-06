#### Задание 6.
- Для успешного развертывания образа, убедитесь что у вас установлен и настроен docker.
- Клонируйте данный репозиторий к себе.
    ```
    git clone https://github.com/viklosh/ds-ex6.git && cd ds-ex6
    ```
- Соберите docker образ.
    ```
    docker build -t hello-java-samp .
    ```
- Запустите контейнер.
    ```
    docker run -d --name hello -p=8080:8080 hello-java-samp
    ```
- Для проверки подключитесь к приложению с помщью браузера.
    ```
    http://your_ip_address:8080/hello-1.0/
    ```