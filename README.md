# Setup

Install [Home Assistant](https://gist.github.com/sclaret/0c37d2eb3ed251420786a1a86e9acccd)

```
cd /config
git init .
git remote add origin git@github.com:sclaret/ha-config.git
git pull origin master
git add configuration.yaml groups.yaml scenes.yaml automations.yaml
git commit
git push --set-upstream origin master
```


# Gotchas

```
Unexpected intent IDs break reference in automation:
scene.lateevening_2
```


# Built-in Config

[https://www.home-assistant.io/integrations/light/](https://www.home-assistant.io/integrations/light/)

[https://www.home-assistant.io/integrations/group/](https://www.home-assistant.io/integrations/group/)

[https://www.home-assistant.io/integrations/light.group/](https://www.home-assistant.io/integrations/light.group/)

[https://www.home-assistant.io/docs/scene/](https://www.home-assistant.io/docs/scene/)

[https://github.com/home-assistant/core/commit/bc5a2da7b72d685e687ff4860d873b1600fa1fb4?branch=bc5a2da7b72d685e687ff4860d873b1600fa1fb4&diff=unified](https://github.com/home-assistant/core/commit/bc5a2da7b72d685e687ff4860d873b1600fa1fb4?branch=bc5a2da7b72d685e687ff4860d873b1600fa1fb4&diff=unified)

[https://community.home-assistant.io/t/transition-for-scenes-is-back-0-109/189781](https://community.home-assistant.io/t/transition-for-scenes-is-back-0-109/189781)


# Extensions

[https://www.awesome-ha.com](https://www.awesome-ha.com/)

[https://github.com/AppDaemon/appdaemon](https://github.com/AppDaemon/appdaemon)

[https://github.com/custom-components/pyscript](https://github.com/custom-components/pyscript)


