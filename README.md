# LIFEHACKAPP6
YOUTUBE LINK : https://youtube.com/shorts/8e-gK8gicPA?feature=share

EXPLAINITION OF THE CODE                                                                                                                                                                                                                                                                                                                This Android application, developed in Kotlin using Android Studio, is an interactive quiz called Science Checkpoint, where users test whether common life tips are true or false. The application follows a multi-activity structure, where each activity is responsible for a specific part of the user experience. The MainActivity serves as the app's entry point and contains a simple user interface built in XML with a LinearLayout, TextViews, and a Button. This screen introduces the app to the user, and when the Start button is clicked, an Intent, which is a messaging object used to request an action from another app component, is used to navigate to the QuizActivity, demonstrating activity navigation.

The QuizActivity is the core component of the application, where the main logic is implemented. It uses arrays to store the quiz questions, their corresponding true-or-false answers, and detailed explanations that provide feedback to the user. Two key variables, index and score, are used to track the current question position and the user’s total correct answers. The loadQuestion function displays the current question based on its index. When the user interacts with the Hack or Myth buttons, the checkAnswer function is triggered, which compares the user’s input with the correct answer stored in the array. If the answer is correct, the score is incremented, and positive feedback is displayed; if incorrect, the correct explanation is shown to enhance learning. The Next button updates the index and loads the next question, allowing the quiz to progress sequentially. Once all questions have been answered, the app uses an Intent to move to the ScoreActivity, passing the score and total number of questions as extra data.

The ScoreActivity retrieves this data using Intent extras and displays the user’s final score along with a performance message that motivates or congratulates the user. It also includes a Review button, which allows the user to navigate to the ReviewActivity. In the ReviewActivity, a loop is used to dynamically generate TextViews for each question and its correct answer, which are added programmatically to a LinearLayout inside a ScrollView, allowing the user to scroll through and review all content. This demonstrates the use of loops, dynamic UI creation, and layouts.

Throughout the application, logging is implemented using Log.d statements to track important events such as activity creation, button clicks, user answers, and score updates. This helps with debugging and shows a clear understanding of the app’s execution flow. Additionally, comments are included within the code to explain the purpose of different sections, and references are provided where external resources, such as online tutorials or documentation, were used. Overall, this application demonstrates key Android development concepts, including activities, intents, arrays, loops, conditional statements, user interaction, UI design, logging, and structured program flow                                                    


REFERENCE 
Android Studio (2024). Android Studio and SDK tools. [online] Android Developers. Available at: https://developer.android.com/studio.

 Social Circle Dental. (n.d.). Boost Your Mood by Smiling and Laughing. [online] Available at: http://www.socialcircledental.com/blog/boost-your-mood-by-smiling-and-laughing.

whitecoat (2020). What is Brain Science? [online] Regional Neurological Associates. Available at: https://regionalneurological.com/what-is-brain-science/.



