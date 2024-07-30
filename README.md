# Портфолио Python @txello

## Оглавление
1. Предисловие  

2. "Чистый код"  
   2.1. [Шифрование](#шифрование)  
   2.2. [Переменные окружения](#переменные-окружения)   
  
3. Сайты  
   3.1. Django  
   3.2. Flask  
   3.3. FastAPI   
   3.4. Streamlit   
   3.5. SQLAlchemy Admin   
  
4. Парсеры  
   4.1. Selenium  
   4.2. BeautifulSoup  
   4.3. Requests  
  
5. Боты  
   5.1. [aiogram](#aiogram)  
   5.2. VKBottle  
   5.3. discord.py  
  
6. Машинное обучение/Нейросети  
   6.1. PyTorch  
   6.2. TensorFlow  
   6.3. Keras  
   6.4. pyTesseract  
   6.5. EasyOCR  
  
7. Инстументы  
   7.1. Обработка информации  
       ⋅⋅7.1.1. [NumPy](#numpy)  
       ⋅⋅7.1.2. [Pandas](#pandas)  
       ⋅⋅7.1.3. [Matplotlib](#matplotlib)  
       ⋅⋅7.1.4. Pillow  
   7.2. Базы данных/Брокеры сообщений  
       ⋅⋅7.2.1. SQLAlchemy  
       ⋅⋅7.2.2. pymongo  
       ⋅⋅7.2.3. kafka-python  
       ⋅⋅7.2.4. RabbitMQ  
       ⋅⋅7.2.5. Redis  
   7.3. Сервисы  
       ⋅⋅7.3.1. gspread  
       ⋅⋅7.3.2. TGStat  
       ⋅⋅7.3.3. Geohelper  
  
8. Контейнеры  
   8.1. Docker  
   8.2. Kubernetes   
  
9. Очереди  
   9.1. Celery  
   9.2. Python RQ  
  
10. Тестирование  
   10.1. PyTest  
   10.2. unittest




# Содержание

## Предисловие

## Чистый код
### Шифрование
* [M16STR](https://github.com/txello/M16STR) - Ассимитричное шифрование.\
  В качестве входных данных используется сообщение, словарь символов и пароль в качестве закрытого ключа.

### Переменные окружения
* [EnvServ](https://github.com/txello/EnvServ) - Чтение переменных окружения и их запись в собственный класс.\
  Использует `python-dotenv`, есть возможность автоматического перевода в нужный тип данных и в нужный формат декодирования.


## Боты
### aiogram
* [tgbot-template](https://github.com/txello/tgbot-template) - Шаблон для профессиональной работы с aiogram.\
  Используется определённый настраиваемый шаблон, внутри которого можно запустить локальный Веб-сервер на `aiohttp`.

## Инструменты
### Numpy
* [Обработка данных котировок акции](https://github.com/txello/portfolio_numpy_1) - Получение котировок акций и их обработка.\
  Используется `numpy`, `pandas` и `yfinance`
### Pandas
* [MorfyDB](https://github.com/txello/morfydb) - Локальная База данных на основе Pandas.\
  Работает как ORM. Есть возможность использования настроек для колонок (`index`, `default` и т.п.)

### Matplotlib
* [Онлайн анализ данных](https://github.com/txello/portfolio_matplotlib_1) - Пример онлайн анализа данных.\
  Используется `pandas`, `matplotlib` и данные с нейроинтейфейса за указанный период
