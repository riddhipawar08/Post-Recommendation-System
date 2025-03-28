<h2>Post Recommendation System<h2>
<h3>Overview<h3>
This project focuses on building an intelligent Post Recommendation System that suggests posts based on user interests, engagement, and work profile. The system prioritizes useful and actionable content by analyzing implicit feedback such as upvotes, saves, and project mappings.
<br>
<h3>Features</h3>
✔ Personalized Post Ranking – Uses implicit feedback for ranking.<br>
✔ Content-Based Filtering – Matches posts based on similarity.<br>
✔ Industry & Work Profile Prioritization – Ensures relevance.<br>
✔ Bayesian Ranking (Wilson Score Interval) – Filters low-quality posts.<br>
✔ Predictive Analytics – Improves recommendations over time.

<h3>Tech Stack</h3>
- Programming Language: Python  <br>
- Libraries Used: Pandas, NumPy, Scikit-learn <br>
- Algorithm: Modified Personalized Ranking, TF-IDF, Bayesian Ranking <br>
- Data Source: User interactions, post metadata

<h3>Recommendation Approach</h3>
The system ranks posts using a 4-step process:

1️⃣ Modified Personalized Ranking (NCF-based)
Assigns different weights to user interactions:<br>
Upvotes = 1
Downvotes = -2
Saves = 3

2️⃣ Content-Based Filtering (TF-IDF, Similarity Matching)
Finds posts similar to a user's saved or engaged posts.

3️⃣ Industry & Work Profile Prioritization
Recommends posts relevant to the user’s domain.

4️⃣ Bayesian Ranking (Wilson Score Interval)
Filters out low-quality or misleading posts.
