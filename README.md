# Deno-demo
Sample code to understand Deno

I hope you have install deno on your install. If not follow install guide on https://deno.land/

- I have made calc.ts file inside libs directory and imported into index.ts. 
- You can also upload calc.ts on remote server and server path to index.ts

Clone repository and run 

```sh
$ cd deno-demo
$ deno run --allow-net index.ts
```
--allow-net flag allows to run on local network or else you will encounter following error
```sh
error: Uncaught PermissionDenied: network access to "0.0.0.0:<PORT>", run again with the --allow-net flag
```

