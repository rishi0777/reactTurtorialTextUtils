## Concepts

### CLS(Cumulative Layout Shifting)

CLS is bad for SEO's, google or any other search engine prefers the website that has very less CLS over websites in which a lot cumulative layout shifting is involved.

So, in this project also when we added the alert each time new alert appears it shifts
whole layoout website downwards which results in bad User Experience so we have removed it
by associating the alert component's div or container with a specified height. So, whether
it is present on screen or not it does not matter, becuase it will consume that much space
on screen and thus shifting occurs, when alert appears.
