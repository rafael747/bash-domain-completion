# bash-domain-completion
Bash domain name completion for some linux commands 

Domains extracted from:

 - Amazon Alexa Top Sites (top 50 from each category)
   - https://www.alexa.com/topsites/category/Top/Computers
   - https://www.alexa.com/topsites/category/Top/Computers/Internet
   - https://www.alexa.com/topsites/category/Top/Computers/Hacking
   - https://www.alexa.com/topsites/category/Top/Computers/Open_Source
   - https://www.alexa.com/topsites/category/Top/Computers/Programming
   - https://www.alexa.com/topsites/category/Top/Computers/Security

 - https://github.com/chubin/awesome-console-services

 - https://www.youtube.com/watch?v=PmiK0JCdh5A

## Instalation 

```shell
   cp top_domains.txt /opt/
   cp domain-completion /etc/bash_completion.d/
   cp keep-domains-updated /etc/cron.weekly/     # to keep domains file updated
```
