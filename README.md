# service-dummy
Dummy @molfar microservice. Simply sends metrics each 1s.
For test it:

```sh
npm test
```

it will do something like this

```sh

> @molfar/service-dummy@1.0.0 test D:\MOLFAR\1\service-dummy                                                                             
> node test                                                                                                                              
                                                                                                                                         
Test run @molfar/service-dummy                                                                                                           
Configure {                                                                                                                              
  _request_id: '1392ab49-d42d-479d-bab6-49f6c5fe07de',                                                                                   
  _instance_id: '1a960bc2-d873-43ae-af3e-ded95065f054',                                                                                  
  _instance_name: '@molfar/service-dummy',                                                                                               
  _instance_path: 'D:\\MOLFAR\\1\\service-dummy\\service.js',                                                                            
  _command: 'configure',                                                                                                                 
  msapi: '1.0.1',                                                                                                                        
  metadata: { id: '@molfar/service-dummy', title: 'Dummy @molfar microservice' },                                                        
  service: { monitoring: { 'time-interval': 1000, transport: [Object] } },                                                               
  data: { status: 'configured' }                                                                                                         
}                                                                                                                                        
Start {                                                                                                                                  
  _request_id: '119184da-a1c3-42a4-8215-dfcfb6d97173',                                                                                   
  _instance_id: '1a960bc2-d873-43ae-af3e-ded95065f054',                                                                                  
  _instance_name: '@molfar/service-dummy',                                                                                               
  _instance_path: 'D:\\MOLFAR\\1\\service-dummy\\service.js',                                                                            
  _command: 'start',                                                                                                                     
  data: { status: 'started' }                                                                                                            
}                                                                                                                                        
Running... 10s  

```
