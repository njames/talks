cf version 8.7.1+9c81242.2023-06-15, Cloud Foundry command line tool
Usage: cf [global options] command [arguments...] [command options]

Before getting started:
  config    login,l      target,t
  help,h    logout,lo    

Application lifecycle:
  apps,a        run-task,rt    events
  push,p        logs           set-env,se
  start,st      ssh            create-app-manifest
  stop,sp       app            delete,d
  restart,rs    env,e          apply-manifest
  restage,rg    scale          revisions

Services integration:
  marketplace,m        create-user-provided-service,cups
  services,s           update-user-provided-service,uups
  create-service,cs    create-service-key,csk
  update-service       delete-service-key,dsk
  delete-service,ds    service-keys,sk
  service              service-key
  bind-service,bs      bind-route-service,brs
  unbind-service,us    unbind-route-service,urs

Route and domain management:
  routes,r        delete-route    create-private-domain,create-domain
  domains         map-route       
  create-route    unmap-route     

Space management:
  spaces            create-space,csp    set-space-role
  space-users       delete-space        unset-space-role
  apply-manifest                        

Org management:
  orgs,o       set-org-role
  org-users    unset-org-role

CLI plugin management:
  plugins           add-plugin-repo      repo-plugins
  install-plugin    list-plugin-repos    

Commands offered by installed plugins:
  bg-deploy                    mta        purge-mta-config
  deploy                       mta-ops    undeploy
  download-mta-op-logs,dmol    mtas       

Global options:
  --help, -h                         Show help
  -v                                 Print API request diagnostics to stdout

TIP: Use 'cf help -a' to see all commands.
