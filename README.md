# The Article: Hyrum's Law (Software Engineering)

**Link:** [https://www.hyrumslaw.com/](https://www.hyrumslaw.com/)

I find Hyrum's Law fascinating because it puts a clear name to a problem every engineer feels: as an API gets popular, users rely on *every* observable behavior, not just the documented ones. That reframes backward compatibility as more than just honoring the spec—it’s about protecting the implicit contract that emerges through real usage.

The article is a useful mental model for designing systems and planning changes. It nudges me to think about testing and observability as ways to detect what people actually depend on, and it reinforces the idea that “small” changes can have large blast radii in a mature system. 

-- Blake Chang

This article made me think about an issue that I hadn't thought about before. I thought it was interesting how the author explained the process by which users come to use aspects of your system that you may not originally have intended for. What you say your API isn't a limit on what users will come to expect of it. It is a good lesson on what to keep in mind when making changes to a widely used system. 

-- Carolina Lee