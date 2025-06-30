# Why do we read so many biographies?

I wanted to know what types of nonfiction books were most popular. I used:
- NYT Bestsellers → Google Books API (for categories) → NYT dataset
- Goodreads nonfiction sample → Google Books → Random sample

I sampled one week every month and generated some quick plots just to see the general shape of the data. This raised more questions after showing how many biographies were on the NYT list.. Is the frequency of biographies representative of how many books are published, or something else?

I got a huge sample of books on Goodreads and filtered them for categories in the same way, which showed that the NYT list was not proportional to the random sample of published nonfiction. 

After getting some critique from my mentoring group, I created the charts on [this webpage](https://nickmuffet.com/lede/books) tho show my results. I was able to get D3 up and running to create the base SVGs for the waffle charts, but not able to style them to showcase them interactively on the page, so they were styled in Figma. There are still things that could be improved (note the vertical rather than horizontal bar charts), but I am moving on for now!

