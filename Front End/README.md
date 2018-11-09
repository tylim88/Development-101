# Front End Technologies

Depend on a lot of factors and needs, libraries will change from time to time.

Here is simple justification of important library that we are going to use.

## 1. React

We use react to build user interface. Personally I like the idea of component, it changes the philosophy of separation of concern. It increase the learning curve as it requires a programmer to have all kinds of knowledge.

However this doesn't necessary increase the workload as others can work on another component without you involved in it. The best thing is, component thinking allows us to reuse the resources easily. I believe this is a correct direction.

But why react? Because there are also library that adopt or gravitate toward component thinking, why react?

Again my answer for this is quite simple: stable and reputed, it is a safe choice.

- More job opportunities, it is easier to get people to join this project especially fot those who want to gain experience.
- It has big ecosystem, resourceful, lots of library created around react.
- Big ecosystem also means, technical problems that you encountered are most likely answered on internet.
- It developed by big company, it will last longer.

If I would pick up another library, I think Vue is a good choice.

## 2. Next

There are actually not much React frameworks out there when come to SSR, presumably Next, Gatsby and After.

It is tricky to render dynamic content with Gatsby, After is fairly new and heavily inspired by Next, the different is After adopt different routing philosophy (which Next will follow).

I simply pick the easier solution, which is Next.

Since the option available is small, question shifted why we use x framework to why we use this kind of framework. Why we use Next/Gatsby /After?

It comes with a lot pros (and cons), but the obvious pro is search engine optimization. In the world of internet, we all at the mercy of Google (joke, Google actually want related site to be discover).

To improve your Google search ranking, you need to tell Google know what you are and the way to do so is to let Google crawl your page and understand your content as much as possible.

But when you send a React page, you are actually sending skeleton html page with no content for Google to crawl, the content only available after client finish render it. Which is why server side rendering is very important.

Yes, google is improving client side rendering crawling algorithm but that is still not enough. plus aside from SEO, there are still number of reasons to use Next.

Other than Next, Gatsby is extremely attractive option is you want to host static page, it is blazing fast, I strongly recommend it.

# 3. Redux

There are a lot of state management library out there, but I dont have much experience to comment on them.

Redux it self is great, but it could be confusing for new learner, I think redux has too much code to do simple thing, not to mention you need middleware to handle async action, adding complexity.

Redux is what most people familiar with plus it play well with Next so I will stick with it for now, but tiny library like Unstated and Meiosis seem worth considering too.