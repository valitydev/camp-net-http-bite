title: Networks
class: animation-fade
layout: true

---

class: impact

# Компьютерные сети
## и их протоколы

---

# Зачем?

--

## Совместное пользование ресурсами

--

* информационными

--

* вычислительными

---

# Что это?

--

.col-4[
* _Сеть_ (network)
]

.col-8[
Множество _узлов_, обменивающихся _данными_ согласно общеизвестным _протоколам_
]

--

.col-4[
* _Узел_ (node)
]

.col-8[
Любое устройство, производящее, перенаправляющее или принимающее _данные_
]

--

.col-4[
* _Хост_ (host)
]

.col-8[
Узел, предоставляющий _ресурсы_ и _сервисы_, и обладающий определённым _адресом_
]

--

.col-4[
* _Протокол_ (protocol)
]

.col-8[
Набор _правил_, которые требуют исполнения _узлами_ для проведения обмена _данными_
]

---

# Протокол

> Protocols are to communication what programming languages are to computations.

--

* задача

--

* медиум

--

* роли участников

--

* формат данных

--

* набор сообщений

--

* порядок обмена сообщениями

---

# Интернет

> The Internet is a network of networks.
>
> <cite>[RFC1122: Requirements for Internet Hosts – Communication Layers](https://tools.ietf.org/html/rfc1122)</cite>

## Многоуровневый набор протоколов

--

.col-6[
* Прикладной уровень (application layer)
]

.col-6[
_HTTP_ / _SSH_ / _IMAP_ / _WebDAV_ / ...
]

--

.col-6[
* Транспортный уровень (transport layer)
]

.col-6[
_TCP_ / _UDP_ / _SCTP_
]

--

.col-6[
* Межсетевой уровень (internet layer)
]

.col-6[
_IP_ / _IPv6_ / _ICMP_ / _IPoAC_ / ...
]

--

.col-6[
* Канальный уровень (link layer)
]

.col-6[
_Ethernet_ / _802.11_ / ...
]

---

# IP over Avian Carriers <small>RFC 1149</small>

> IPoAC has been successfully implemented, but for only nine packets of data, with a packet loss ratio of 55% (due to operator error), and a response time ranging from 3000 seconds (≈54 minutes) to over 6000 seconds (≈1.77 hours).
>
> <cite>[The informal report from the RFC 1149 event](https://www.blug.linux.no/rfc1149/writeup/)</cite>

--

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/53/Pigeon_krakow.jpg/1024px-Pigeon_krakow.jpg" style="width:50%; margin: 0 25%;"/>

---

# Модель OSI

--

### 7. Прикладной уровень

### 6. Уровень представления данных

### 5. Сессионный уровень

### 4. Транспортный уровень

### 3. Сетевой уровень

### 2. Канальный уровень

### 1. Физический уровень

---

class: impact

# Пока всё
## Спасибо за внимание
