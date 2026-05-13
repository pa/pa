<p align="center">
  <img src="https://raw.githubusercontent.com/pa/pa/master/assets/hero.svg?v=2" alt="$ terraform apply -auto-approve  module.engineer.pa.role = Tech Lead DevOps  Apply complete! 4 added, 0 destroyed." width="800"/>
</p>

<h3><code>$ kubectl get skills -o wide</code></h3>

```text
NAME              CATEGORY      LEVEL    YEARS   STATUS    NODE
kubernetes        container     senior   8       Running   prod
terraform         iac           senior   7       Running   prod
aws               cloud         senior   9       Running   prod
gcp               cloud         mid      3       Running   prod
azure             cloud         mid      4       Running   prod
helm              container     senior   6       Running   prod
argocd            cicd          senior   3       Running   prod
prometheus        observe       senior   5       Running   prod
grafana           observe       senior   5       Running   prod
teleport          access        senior   3       Running   prod
go                language      mid      4       Running   prod
python            language      senior   8       Running   prod
rust              language      junior   1       Pending   stage
typescript        language      mid      3       Running   prod
```

<h3><code>$ kubectl get projects --selector=visibility=public</code></h3>

```text
NAME              STATUS    KIND        VERSION   URL
termstack         Running   Rust/TUI    v0.4      github.com/pa/termstack
gen-chart         Running   Web/React   v1.2      github.com/pa/gen-chart
image-to-ascii    Running   Web/Vite    v0.5      github.com/pa/image-to-ascii
dotman            Running   Go/CLI      v1.0      github.com/pa/dotman
```

> Archived workloads at `pramodhayyappan.dev/projects`.

<h3><code>$ git log --oneline experience.git</code></h3>

```text
* HEAD       2022-09 → present     feat: Tech Lead DevOps @ Facets.cloud
* d49a2ef    2021-10 → 2022-09     feat: Digital Engineering Lead @ NTT Data
* 7c12b8a    2020-11 → 2021-10     refactor: Sr. DevOps Specialist @ Flux7
* 5e3f1d2    2018-10 → 2020-10     feat: DevOps Engineer @ Flux7
* 0a1e72b    2015-10 → 2018-08     init: Software Engineer @ Virtusa
```

<h3><code>$ tail -f /var/log/now.log</code></h3>

```log
2026-05-09T14:23 [INFO ] facets.cloud  Building IDP — zero-trust, observability, self-service
2026-05-09T14:23 [INFO ] termstack     Maintaining v0.4, planning streaming-data v0.5
2026-05-09T14:23 [INFO ] writing       New posts at pramodhayyappan.dev/blog
2026-05-09T14:23 [DEBUG] reading       distributed-systems lit, eBPF observability
```

<h3><code>$ curl -s endpoint=connect</code></h3>

```text
linkedin     linkedin.com/in/pramodhayyappan
website      pramodhayyappan.dev
email        pramodh.ayyappan@hotmail.com
location     chennai, india
```

<h3><code>$ kubectl top github --user=pa</code></h3>

```text
USER   REPOS    FOLLOWERS    FOLLOWING    GISTS    SINCE
pa     38       18           31           1        2018-10

LANGUAGE          USAGE                              REPOS
python            █████████████████████████            7
shell             ███████████░░░░░░░░░░░░░░            3
go                ███████████░░░░░░░░░░░░░░            3
javascript        ███████░░░░░░░░░░░░░░░░░░            2
hcl               ███████░░░░░░░░░░░░░░░░░░            2
typescript        ████░░░░░░░░░░░░░░░░░░░░░            1
```

> Snapshot: 2026-05-09 · sourced from `gh api users/pa`

---

<sub><code>[OK]</code> all systems nominal · <code>uptime</code> 11y · <code>load</code> 3.14 · <code>status</code> shipping ▊</sub>
