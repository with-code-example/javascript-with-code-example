---
title: "My First Post"
date: 2023-08-01
draft: false
tags: ["tutorial", "programming"]
categories: ["technology", "web-development"]
slug: "my-first-post"
description: "This is my first Hugo post."
author: "John Doe"
# featured_image: "/images/first-post.jpg"
# aliases:
#   - "/old-url-of-post"
toc: true
---

When creating a new post in Hugo, you can add various attributes (front matter) to the post file using YAML, TOML, or JSON syntax. These attributes provide metadata about the post and help Hugo organize and render the content correctly. Here are some common attributes you can use in a Hugo post file:

1. **title**: The title of the post.

2. **date**: The date of the post. You can use a specific date or use `now` to set the current date automatically.

3. **draft**: (Optional) A boolean value (`true` or `false`) to indicate whether the post is a draft. Drafts are not published when generating the site with the `hugo` command, but you can preview them using `hugo server --buildDrafts`.

4. **tags**: (Optional) An array of tags to categorize the post. For example, `tags: ["tutorial", "programming"]`.

5. **categories**: (Optional) An array of categories to classify the post. For example, `categories: ["technology", "web-development"]`.

6. **slug**: (Optional) The URL slug for the post. If not provided, Hugo generates it from the title automatically.

7. **description**: (Optional) A short description of the post.

8. **author**: (Optional) The name of the author of the post.

9. **featured_image**: (Optional) The URL or path to a featured image for the post.

10. **aliases**: (Optional) An array of alternative URLs that should redirect to this post. Useful for setting up redirects from old URLs.

11. **toc**: (Optional) A boolean value (`true` or `false`) to enable or disable the table of contents for the post.

Here's an example of a Hugo post with all the attributes mentioned above:

```markdown
---
title: "My First Post"
date: 2023-08-01
draft: false
tags: ["tutorial", "programming"]
categories: ["technology", "web-development"]
slug: "my-first-post"
description: "This is my first Hugo post."
author: "John Doe"
featured_image: "/images/first-post.jpg"
aliases:
  - "/old-url-of-post"
toc: true
---

This is the content of my first post.
```

Please note that you don't have to include all attributes in every post. Use the ones that are relevant to your content and leave out the rest. The front matter attributes are optional and flexible based on your specific needs for each post.