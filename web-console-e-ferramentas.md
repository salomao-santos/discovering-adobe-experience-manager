Web Console & Ferramentas
==================

[Discovering Adobe Experience Manager (AEM)](README.md) / [Web Console & Ferramentas](web-console-e-ferramentas.md)

-------------

1. CRXDE Lite:

    * Acesse `http://<host>:<port>/crx/de/index.jsp`

    * Exemplo:

      * [http://127.0.0.1:4502/crx/de/index.jsp](http://127.0.0.1:4502/crx/de/index.jsp) 



2. CRX Explorer:

    * Acesse  `http://<host>:<port>/crx/explorer/index.jsp`.

    * Exemplo:

      * [http://127.0.0.1:4502/crx/explorer/index.jsp](http://127.0.0.1:4502/crx/explorer/index.jsp) 

3. Package:

    * Acesse  `http://<host>:<port>/crx/packmgr/index.jsp`.

    * Exemplo:

      * [http://127.0.0.1:4502/crx/packmgr/index.jsp](http://127.0.0.1:4502/crx/packmgr/index.jsp)


4.  Web Console:

    * Acesse  `http://<host>:<port>/system/console/configMgr`.

    * Exemplo:

      * [http://127.0.0.1:4502/system/console/configMgr](http://127.0.0.1:4502/system/console/configMgr)


5. OSGi Bundles Console:

    * Acesse  `http://<host>:<port>/system/console/bundles`

    * Exemplo:

      * [http://127.0.0.1:4502/system/console/bundles](http://127.0.0.1:4502/system/console/bundles)

6. Workflows Console:

    * Acesse  `http://<host>:<port>/libs/cq/workflow/content/console`

    * Exemplo:

      * [http://127.0.0.1:4502/libs/cq/workflow/content/console](http://127.0.0.1:4502/libs/cq/workflow/content/console)


7. Useradmin Console:

    * Acesse  `http://<host>:<port>/libs/granite/security/content/useradmin.html`

    * Exemplo:

      * [http://127.0.0.1:4502/libs/granite/security/content/useradmin.html](http://127.0.0.1:4502/libs/granite/security/content/useradmin.html)


8. Groupadmin Console:

    * Acesse  `http://<host>:<port>/libs/granite/security/content/groupadmin.html`

    * Exemplo:

      * [http://127.0.0.1:4502/libs/granite/security/content/groupadmin.html](http://127.0.0.1:4502/libs/granite/security/content/groupadmin.html) 


9. Users and Groups Management Console:

    * Acesse  `http://<host>:<port>/useradmin`

    * Exemplo:

      * [http://127.0.0.1:4502/useradmin](http://127.0.0.1:4502/useradmin)


10. Siteadmin Console:

    * Acesse  `http://<host>:<port>/sites.html/content`

    * Exemplo:

      * [http://127.0.0.1:4502/sites.html/content](http://127.0.0.1:4502/sites.html/content) 


11. DAM Console:

    * Acesse  `http://<host>:<port>/assets.html/content/dam`.

    * Exemplo:

      * [http://127.0.0.1:4502/assets.html/content/dam](http://127.0.0.1:4502/assets.html/content/dam) 


12. Force AEM to rebuild ClientLibs via this url:

    * Acesse  `http://<host>:<port>/libs/granite/ui/content/dumplibs.rebuild.html`.

    * Exemplo:

      * [http://127.0.0.1:4502/libs/granite/ui/content/dumplibs.rebuild.html](http://127.0.0.1:4502/libs/granite/ui/content/dumplibs.rebuild.html) 


13. Diagnosis Console:

    * Acesse  `http://<host>:<port>/libs/granite/operations/content/diagnosis.html`

    * Exemplo:

      * [http://127.0.0.1:4502/libs/granite/operations/content/diagnosis.html](http://127.0.0.1:4502/libs/granite/operations/content/diagnosis.html)

14. Acesse as últimas 1000 linhas do arquivo error.log:

    * Acesse  `http://<host>:<port>/system/console/slinglog/tailer.txt?tail=1000&grep=*&name=%2Flogs%2Ferror.log`

    * Exemplo:

       http://127.0.0.1:4502/system/console/slinglog/tailer.txt?tail=1000&grep=*&name=%2Flogs%2Ferror.log 

15. Acesse as últimas 1000 linhas do arquivo request.log:

     * Acesse  `http://<host>:<port>/system/console/slinglog/tailer.txt?tail=1000&grep=&name=%2Flogs%2Frequest.log`

     * Exemplo:

         http://127.0.0.1:4502/system/console/slinglog/tailer.txt?tail=1000&grep=&name=%2Flogs%2Frequest.log 

16. Replication Console:

    * Acesse  `http://<host>:<port>/etc/replication.html`

    * Exemplo:

      * [http://127.0.0.1:4502/etc/replication.html](http://127.0.0.1:4502/etc/replication.html) 

17. Informações sobre a instância do AEM, incluindo a versão:

    * Acesse  `http://<host>:<port>/libs/cq/core/content/welcome.html`.

    * Exemplo:

      * [http://127.0.0.1:4502/libs/cq/core/content/welcome.html](http://127.0.0.1:4502/libs/cq/core/content/welcome.html) 

18. Bundle location in the Java Content Repository:

    * Lembre de mudar {project}, pelo nome do seu projeto 

    * Acesse  `http://<host>:<port>/crx/de/index.jsp#/apps/{project}/install`

    * Exemplo:

      * [http://127.0.0.1:4502/crx/de/index.jsp#/apps/sample-site/install](http://127.0.0.1:4502/crx/de/index.jsp#/apps/sample-site/install) 


19. System Config in the Java Content Repository:

   * Acesse  `http://<host>:<port>/crx/de/index.jsp#/apps/system/config`

   * Exemplo:

      * [http://127.0.0.1:4502/crx/de/index.jsp#/apps/system/config](http://127.0.0.1:4502/crx/de/index.jsp#/apps/system/config) 

  
20. System Overview 
   
   * Acesse  `http://<host>:<port>/libs/granite/operations/content/systemoverview.html`

   * Exemplo:

      * [http://127.0.0.1:4502/libs/granite/operations/content/systemoverview.html](http://127.0.0.1:4502/libs/granite/operations/content/systemoverview.html)

21. Dependências do AEM:

     * Acesse  `http://<host>:<port>/system/console/depfinder`
     * Exemplo: [http://127.0.0.1:4502/system/console/depfinder]

22. QueryBuilder debugger:

    * [Documentação](https://experienceleague.adobe.com/docs/experience-manager-64/developing/platform/query-builder/querybuilder-api.html?lang=en#platform)

    * Acesse  `http://<host>:<port>/libs/cq/search/content/querydebug.html`

    * Exemplo:

      * [http://127.0.0.1:4502/libs/cq/search/content/querydebug.html](http://127.0.0.1:4502/libs/cq/search/content/querydebug.html) 

23. [URI Decoder] (http://coderstoolbox.net/string/#!encoding=url&action=decode&charset=utf_8)

24. Status Sling Scheduler
   * Acesse  `http://<host>:<port>/system/console/status-slingscheduler`
   * Exemplo:
      * [http://127.0.0.1:4502/system/console/status-slingscheduler](http://127.0.0.1:4502/system/console/status-slingscheduler) 

25.

26. Run Mode 
 
   * Acesse  `http://<host>:<port>/system/console/status-slingsettings`
   * Exemplo:
      * [http://127.0.0.1:4502/system/console/status-slingsettings](http://127.0.0.1:4502/system/console/status-slingsettings) 
-------------

Referências
===========
 1. https://experienceleague.adobe.com/docs/experience-manager-65/deploying/configuring/configuring-web-console.html?lang=en#components
