# Cluster and Cloud Computing - Intro

## 一、Definition

### 1. Utility Computing

​     A pool of virtualized computer resources that IT can access **on demand.**

### 2. Cloud Computing

​     Cloud computing describes the use of software,storage or processing services delivered **over the Internet** from **massive datacentres**.

### 3. Caas Faas Iaas Saas Paas



## 二、Why Cloud

### 1. Result of over-provisioning:underutilization ![img](https://cdn.nlark.com/yuque/0/2021/png/12763607/1635744603570-945019ff-1055-442b-8b82-c7120f62c8c7.png)

### 2. Heavy penalty from under provisioning (Loss of revenue and user)



![img](https://cdn.nlark.com/yuque/0/2021/png/12763607/1635744973294-fce5940c-b5b6-4c57-9c8d-400386b8b886.png)

### 3. Cloud:Dynamic resource scaling,instead of provisioning for peak![img](https://cdn.nlark.com/yuque/0/2021/png/12763607/1635745102611-102f557c-c6c8-4103-8eed-066e5d8d8010.png)

## 三、Virtualization

### 1. Virtual Machines:Hardware Abstraction Layer

![img](https://cdn.nlark.com/yuque/0/2021/png/12763607/1635745222567-8c1160e9-1f9e-4481-a059-d864d0aeedf2.png)

使用VMM(Virtual Machine Monitor)在hardware上进行抽象，公用一个hardware但是可以有多个os以上的。

### 2. Container:Os-Level Vitualization(rapidly development)

使用Container在os层进行抽象，公用一个os，但是可以有多个os以上的

![img](https://cdn.nlark.com/yuque/0/2021/png/12763607/1635745607153-a1d4e6d0-625d-4857-9d20-2ea61028f791.png)

### 3. Containers on top of VMs.

![img](https://cdn.nlark.com/yuque/0/2021/png/12763607/1635745693081-90a46c01-6e17-482a-9821-503ce1e3a0e7.png)

## 四、Cloud Deployment Model

### 1. Public Cloud

​    Provisioned for **open use for public**,owned by organization selling cloud services.

### 2. Private Cloud

   Provisioned for a **sigle organization**,manager internally or by  a third party

### 3. Community Clouds

   Provisioned for exclusive user by a **specific community of subscriber**s that have shared concerns,managed by an organization or third party.

### 4. Hybrid Cloud

  Public + Private

  Cloud infrastucture is a **composition** of two or more distinct cloud infrastructure.



