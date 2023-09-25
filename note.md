`To creating project from scratch we need followiing command: `

```
    npm init -y
```

## Dependecies for nest js

```
    npm i @nestjs/common@7.6.17 @nestjs/core@7.6.17 @nestjs/platform-express@7.6.17 reflect-metadata@0.1.13 typescript@4.3.2
```

## To run code that build from scratch following code need:

```
npx ts-node-dev src/main.ts
```
### File naming conventions in nest js 
```
    .........................           CONVENTIONS:
    .          main.ts      .       One clas per file (some exceptions)
    .........................
    .                       .
    . function bootstrap    .
    .                       .
    .                       .
    .........................



    .............................
    .   app.controller.ts       .       Class name should include the kind
    .............................       of thing we are creating
    .                           .
    .   class AppController {}  .
    .                           .
    .                           .
    .............................
                                        Name of class and name of file should
                                        always match up
    .............................
    .        app.module.ts      .
    .............................
    .                           .       Filename template:
    .   class AppModule {}      .           name.type_of_thing.ts
    .                           .
    .                           .
    .............................


```
### ASDFAS