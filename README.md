### Hi 👋, I'm Java不良人

### About me

```go
package main

import (
	"fmt"
)

type Bio map[string]interface{}

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%s: %s\n", k, v)
	}
}

func GetBio() Bio {
	return Bio{
		"Currently learning":        "C++, Java, Go, Qt, MySQL, Redis, Kafka, MongoDB, Elasticsearch",
		"Looking to collaborate on": "C++, Java and Go related projects",
		"Ask me about":              "Anything related to what I am currently learning",
		"The direction of efforts":  "Be an excellent programmer and create many meaningful open source projects",
	}
}
```

### GitHub Analytics

<a href="https://github.com/wang0329">
   <img align="" height="137.9px" src="https://github-readme-stats.vercel.app/api?username=wang0329&include_all_commits=true&count_private=true&hide_title=true&show_icons=true&include_all_commits=true&line_height=21"/>
   <img align="" height="137.9px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=wang0329&hide_title=true&layout=compact"/>
</a>
